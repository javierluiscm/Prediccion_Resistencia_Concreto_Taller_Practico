# **📊 Predicción de la Resistencia del Concreto mediante Modelos de Regresión.**

## **Descripción del Proyecto**

Este proyecto desarrolla y compara diferentes técnicas de regresión lineal para estimar la resistencia a la compresión del concreto (MPa) a partir de variables relacionadas con su composición y proceso de curado.

El análisis se realiza sobre un conjunto de datos históricos suministrado por una empresa del sector de materiales de construcción, con el objetivo de apoyar la toma de decisiones en el diseño y control de calidad de mezclas de concreto.

## **Objetivo**

Construir y evaluar modelos predictivos capaces de estimar la resistencia del concreto utilizando variables asociadas a la dosificación de materiales y condiciones de curado.

## **Problema de Negocio**

La resistencia del concreto es uno de los principales indicadores de calidad en la industria de la construcción.

La empresa busca aprovechar la información histórica de sus mezclas para:
* Mejorar la estimación de la resistencia final.
* Reducir costos asociados a pruebas físicas.
* Optimizar la formulación de mezclas.
* Fortalecer los procesos de control de calidad.

## **Variable objetivo**
Concrete Compressive Strength (MPa)

## **Variables predictoras**
* Cement
* Blast Furnace Slag
* Fly Ash
* Water
* Superplasticizer
* Coarse Aggregate
* Fine Aggregate
* Age

# Metodología

1. Exploración y comprensión de los datos
* Carga del dataset
* Revisión de dimensiones
* Identificación de valores faltantes
* Estadística descriptiva
* Definición de variables dependientes e independientes

# Análisis de relaciones
* Matriz de correlación
* Heatmap de correlaciones
* Análisis de variables más influyentes
* Evaluación de multicolinealidad

# Construcción de modelos
* Modelo 1: Regresión Lineal (OLS)
* Modelo 2: Regresión Ridge
* Modelo 3: Regresión Lasso

# Fase Entrenamiento y prueba de datos.
* Entrenamiento: 80%
* Prueba: 20%
* Random State: 42

# Tecnologías Utilizadas
* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels

## Autor
Luis Javier Cuchimba Morales
- Analista Senior de Portafolio y Riesgo de Crédito
- Científico de Datos en Formación
