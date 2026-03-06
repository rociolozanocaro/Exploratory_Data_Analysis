# 🐾 Veterinary Clinical Dataset — Exploratory Data Analysis (EDA)

![Logo de Mariana Rocío L. Analytics](logo.webp)

![Python 3.11](https://img.shields.io/badge/Python-3.11-blue)
![pandas 1.6.2](https://img.shields.io/badge/pandas-1.6.2-green)
![NumPy 1.26.0](https://img.shields.io/badge/NumPy-1.26.0-orange)
![Matplotlib 3.8.0](https://img.shields.io/badge/Matplotlib-3.8.0-red)
![Seaborn 0.12.2](https://img.shields.io/badge/Seaborn-0.12.2-purple)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow)

## 📌 Descripción del proyecto

Este proyecto consiste en un **análisis exploratorio de datos (EDA)** aplicado a un dataset clínico veterinario, con el objetivo de comprender las características demográficas y clínicas de perros y gatos atendidos en un contexto veterinario. El análisis se centra en variables como especie, edad, peso, raza, síntomas, historial médico y diagnósticos, utilizando técnicas estadísticas descriptivas y visualizaciones para identificar patrones y relaciones relevantes.

## 👥 Contribuyentes y roles

- **Nombre:** Rocio Lozano Caro — **Rol:** Análisis exploratorio de datos, visualización, limpieza de datos
- **Nombre:** Mariana Moreno Henao — **Rol:** Apoyo en análisis, revisión de resultados y documentación

## 🎯 Objetivos del proyecto

- Comprender la distribución de edad y peso en perros y gatos
- Analizar diferencias entre especies y razas
- Explorar la relación entre edad, peso y variables clínicas (síntomas, historial médico y diagnósticos)
- Identificar patrones descriptivos relevantes en un contexto veterinario
- Documentar un flujo de análisis reproducible en Python

## 🏗️ Arquitectura del pipeline

1. Carga del dataset
2. Exploración inicial: revisión de estructura, tipos de variables, primeros registros
3. Limpieza de datos: manejo de valores faltantes, corrección de inconsistencias
4. Análisis exploratorio: estadísticos descriptivos, visualizaciones por especie, raza y variables clínicas
5. Conclusiones basadas en datos

## 📁 Estructura del repositorio

- ├── EDA_Veterinary_Clinical_Dataset.ipynb
- ├── README.md


## 🛠️ Tecnologías y librerías usadas

**Python 3**, **pandas**, **numpy**, **matplotlib**, **seaborn**

*(Las versiones exactas pueden consultarse en el entorno de ejecución del notebook)*

## 🧹 Proceso de limpieza y normalización de datos

- Revisión de valores faltantes en columnas numéricas y categóricas
- Eliminación o filtrado de registros incompletos cuando no era posible una imputación coherente
- Aseguramiento de tipos de datos correctos para edad y peso
- Estandarización de categorías textuales (especie, raza, historial médico y síntomas) para evitar duplicados semánticos

## 📊 Dataset final

El análisis se realizó sobre el dataset original, sin generar un archivo final separado. Las transformaciones y filtrados se aplican directamente en el notebook para garantizar trazabilidad y reproducibilidad.

**Principales columnas utilizadas:** `AnimalName` (especie), `Breed`, `Age`, `Weight_kg`, `Symptoms`, `MedicalHistory`, `Diagnosis`

## 📐 Nota metodológica y enfoque estadístico

El proyecto utiliza un enfoque descriptivo y exploratorio, basado en estadísticos descriptivos (media, mediana, desviación estándar), comparaciones entre grupos categóricos y visualización de distribuciones y relaciones entre variables y prueva hipótesis.
 

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Abrir el archivo `EDA_Veterinary_Clinical_Dataset.ipynb` en **Jupyter Notebook** o **Google Colab**
3. Instalar las dependencias necesarias:
```bash
   pip install pandas numpy matplotlib seaborn
```
4. Ejecutar las celdas en orden para reproducir el análisis completo

## 📚 Referencias

- **Dataset:** [Veterinary Clinical Dataset (Kaggle)](https://www.kaggle.com/)
- Documentación oficial de **pandas**, **seaborn** y **matplotlib**

## 🔍 Conclusiones basadas en los datos

- Existen diferencias claras de peso y edad entre perros y gatos, visibles en las distribuciones.
- El peso promedio varía significativamente entre razas, especialmente en perros.
- Algunos síntomas e historiales médicos se concentran en rangos específicos de edad segun la especie.
- Los boxplots permiten identificar variabilidad y valores atípicos relevantes en edad y peso según condiciones clínicas.
- Las visualizaciones facilitan la comparación entre especies y categorías médicas sin necesidad de modelos complejos.
- No se ha encontrado relación lineal entre la edad y el peso. 
