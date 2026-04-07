# Pipeline de Procesamiento de Datos con PySpark

##  Descripción

Este proyecto consiste en la construcción de un pipeline de procesamiento de datos utilizando PySpark, orientado a trabajar con datos de gran volumen y alta complejidad.

Integra procesos de limpieza, transformación y preparación de datos para su posterior análisis y modelamiento.

---

## Tecnologías

* PySpark
* Spark SQL
* Python

---

##  Estructura del pipeline

### 1. Ingesta de datos

* Carga de datos a gran escala
* Inspección de esquemas

### 2. Limpieza de datos

* Tratamiento de valores nulos
* Filtrado de registros inconsistentes
* Validación de datos

### 3. Transformación de datos

* Transformación de variables
* Escalamiento logarítmico
* Estructuración del dataset

### 4. Ingeniería de variables

* Construcción de variables basadas en comportamiento (RFM)
* Preparación para modelos de machine learning

---

## Modelamiento

### Regresión logística

* Modelo de clasificación binaria
* Alto desempeño (ROC ≈ 0.98)

### Clustering (K-means)

* Exploración de estructuras internas
* Identificación de desbalance y limitaciones

---

## Resultados

El pipeline permitió transformar datos complejos y desestructurados en un conjunto de datos consistente y apto para análisis y modelamiento.

Además, evidenció la importancia del preprocesamiento en el rendimiento de los modelos.

---

## Aprendizajes clave

* La calidad de los datos es crítica en entornos de Big Data
* El procesamiento distribuido requiere validación rigurosa
* El rendimiento de los modelos depende fuertemente del preprocesamiento
* Las métricas deben complementarse con análisis crítico

---

## Limitaciones

* Sensibilidad de K-means a la distribución de los datos
* Dificultades con alta dimensionalidad
* Dependencia de decisiones de preprocesamiento
