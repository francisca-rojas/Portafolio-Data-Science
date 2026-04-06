# 👩‍💻 Francisca Rojas — Portafolio de Ciencia de Datos

## 🚀 Sobre mí

Soy Licenciada en Física con formación en análisis cuantitativo y pensamiento científico, actualmente especializándome en Ciencia de Datos.

A lo largo de mi formación he desarrollado proyectos enfocados en análisis de datos, machine learning y procesamiento en entornos de Big Data, enfrentando desafíos reales como limpieza de datos, ingeniería de variables y evaluación crítica de modelos.

Mi experiencia en docencia me ha permitido desarrollar habilidades de comunicación, pensamiento estructurado y resolución de problemas, las cuales complemento con herramientas técnicas para generar soluciones basadas en datos.

Me interesa desarrollarme en el área de analítica avanzada y machine learning, aportando valor mediante el uso estratégico de datos en la toma de decisiones.

---

## 🛠️ Tecnologías y herramientas

* **Lenguajes:** Python
* **Big Data:** PySpark, Spark SQL, MLlib
* **Machine Learning:** Scikit-learn
* **Análisis de datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn

---

## 📂 Proyectos destacados

### 📊 Predicción de gasto en clientes e-commerce

Desarrollo de un modelo de clasificación para identificar clientes de alto valor en una plataforma de comercio electrónico.

* Ingeniería de variables basada en comportamiento de compra 
* Entrenamiento de modelos de regresión
* Optimización de modelos con reducción dimensional y regularización
* Evaluación mediante análisis de error, explicabilidad y estabilidad

🔎 **Valor:** Permite predecir comportamiento de gastos
---

### 🧩 Segmentación de clientes (Clustering)

Análisis de segmentación de clientes utilizando técnicas de aprendizaje no supervisado.

* Preprocesamiento de datos (limpieza, escalado y transformación)
* Aplicación de reducción de dimensional, K-means, Agrupamiento Jerárquico y DBSCAN
* Evaluación de resultados mediante métricas como silhouette score
* Interpretación de segmentos desde una perspectiva de negocio

🔎 **Valor:** Exploración de patrones de comportamiento para segmentación comercial.

---

### ⚡ Retail Analytics Pipeline con Spark

Desarrollo de un pipeline de datos en entorno Big Data para análisis de clientes en retail.

* Procesamiento de datos con PySpark y consultas SQL
* Limpieza y transformación de datos a gran escala
* Integración de modelos de machine learning
* Enfoque en calidad de datos y consistencia de la información

🔎 **Valor:** Construcción de base analítica para toma de decisiones en contextos de alto volumen de datos.

---

## ⭐ Caso de Estudio: Retail Analytics Pipeline con Spark

### 📌 Problema

Se trabajó con datos de retail en línea con el objetivo de analizar el comportamiento de clientes y construir un pipeline de datos que permitiera aplicar modelos de machine learning en un entorno de Big Data.

---

### ⚡ Desafío

El principal desafío fue la baja calidad y complejidad de los datos, junto con la adaptación a nuevas herramientas.

Principales problemas:

* Datos nulos en distintos formatos
* Registros inconsistentes de ventas y devoluciones
* Clientes sin identificación
* Productos sin categorización clara
* Variables no preparadas para modelos supervisados

---

### 💡 Solución

Se implementó un proceso de limpieza y transformación de datos utilizando PySpark y consultas SQL.

Acciones principales:

* Eliminación e imputación de valores nulos
* Filtrado de transacciones para considerar solo ventas reales
* Selección de clientes válidos
* Transformación logarítmica para reducir impacto de outliers
* Ingeniería de variables basada en modelo RFM

Se construyó además una variable objetivo para aplicar modelos supervisados orientados a identificar clientes de alto valor.

---

### 🤖 Modelado

#### Regresión logística

Se entrenó un modelo de clasificación para identificar clientes de alto valor, obteniendo un desempeño alto (ROC ≈ 0.98).

---

#### Segmentación de clientes (K-means)

Se aplicó K-means para segmentar clientes en base a su comportamiento.

En una primera etapa, los resultados evidenciaron limitaciones importantes:

* Clusters altamente desbalanceados
* Segmentaciones con alto silhouette score pero baja utilidad práctica
* Baja interpretabilidad desde el negocio

Esto evidenció que las métricas por sí solas no garantizan una segmentación útil.

Sin embargo, mediante ajustes en el preprocesamiento y en la selección de parámetros, se logró identificar una configuración de clusters más equilibrada y coherente desde una perspectiva de negocio, aun cuando las métricas no eran óptimas.

Esta segmentación permitió distinguir grupos de clientes con comportamientos diferenciados, generando una base interpretable para posibles estrategias comerciales.

---

### ⚠️ Limitaciones

El análisis mostró que K-means presenta limitaciones en este contexto debido a:

* Sensibilidad a outliers
* Suposición de clusters esféricos
* Problemas con datos desbalanceados
* Alta dimensionalidad

---

### 🧠 Aprendizajes

* La calidad de los datos es crítica en cualquier proyecto de analítica
* Las métricas no siempre reflejan valor real para el negocio
* Es posible obtener resultados útiles incluso cuando los indicadores no son ideales
* La interpretación y el contexto de negocio son fundamentales en la toma de decisiones

---

### 🎯 ¿Por qué este proyecto?

Este proyecto representa un punto clave en mi formación, ya que integré conocimientos de procesamiento de datos, machine learning y Big Data, enfrentando desafíos similares a los de un entorno real.

---

## 📫 Contacto

* LinkedIn: *https://www.linkedin.com/in/francisca-rojas-634b21389/*
* Email: *f.nada.todo@gmail.com*
* GitHub: *https://github.com/francisca-rojas*

---
