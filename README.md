# Data Engineering Assessment - PySpark & SQL

Este repositorio contiene la solución a los ejercicios prácticos de ingeniería de datos, enfocados en procesamiento distribuido, limpieza de datos y analítica avanzada.

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Motor de Procesamiento:** Apache Spark (PySpark)
* **Base de Datos:** SQLite (SQL estándar)
* **Formatos de Datos:** JSON, Parquet, CSV

## Contenido del Proyecto

### 1. Análisis Deportivo (FIFA World Cup) 
Procesamiento de datos de partidos y jugadores utilizando **SQL** y **PySpark**.
* **SQL:** Consultas complejas, `CASE WHEN`, Joins y lógica de clasificación de equipos.
* **PySpark:**
    * Limpieza de tipos de datos (`Cast`).
    * Uso avanzado de **Window Functions** (`rank`, `min`) para jerarquizar jugadores por país.
    * Generación de estructuras anidadas para exportación JSON.

### 2. Geolocalización Centros Educativos Madrid 
Cálculo de centroides y distancias para optimización de puntos de encuentro.
* Ingesta de datos semi-estructurados (JSON multiline).
* Limpieza de calidad de datos (filtrado de coordenadas nulas).
* Creación de **UDFs (User Defined Functions)** para cálculo de **Distancia Euclidiana**.
* Ranking geoespacial mediante particionamiento por titularidad del centro.

## Cómo ejecutar
El proyecto está diseñado para correr en entornos como **Google Colab** o **Databricks**.
1. Cargar los datasets (`CENTROS_EDUCACION_MADRID.json`, etc.) en el entorno.
2. Ejecutar los notebooks secuencialmente.
