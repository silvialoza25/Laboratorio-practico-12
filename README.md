# Laboratorio-practico-12
Repositorio de analítica predictiva con el dataset Diabetes de scikit-learn (442 muestras, 10 variables clínicas). Incluye EDA, regresión, clasificación, Random Forest, validación cruzada y modelos ARIMA para predicción y análisis de series temporales.
📊 Laboratorio de Analítica Predictiva con Python – Dataset Diabetes

Este repositorio contiene un conjunto estructurado de experimentos enfocados en la construcción, evaluación y validación de modelos de Machine Learning y Series Temporales, utilizando el dataset de diabetes disponible en scikit-learn.

🎯 Objetivo

Desarrollar un pipeline completo de análisis predictivo que abarque:

Modelos de regresión (predicción continua)
Modelos de clasificación binaria
Técnicas de ensemble learning
Validación robusta de modelos
Introducción a series temporales (ARIMA)
🧬 Descripción del Dataset: Diabetes

El dataset Diabetes es un conjunto de datos clásico en problemas de regresión, ampliamente utilizado para benchmarking en modelos de Machine Learning.

📌 Contexto
Contiene información médica de pacientes con diabetes
El objetivo es predecir la progresión de la enfermedad un año después, a partir de variables clínicas
Todos los datos están preprocesados y normalizados (media = 0, varianza = 1), lo cual facilita el modelado
📊 Estructura del Dataset
Número de muestras: 442 pacientes
Número de variables predictoras: 10 features
Variable objetivo (target): Progresión cuantitativa de la enfermedad
🔍 Variables (Features)
Variable	Descripción
age	Edad del paciente
sex	Sexo
bmi	Índice de masa corporal (variable clave en el análisis)
bp	Presión arterial promedio
s1	Colesterol total
s2	Lipoproteínas de baja densidad (LDL)
s3	Lipoproteínas de alta densidad (HDL)
s4	Relación colesterol total / HDL
s5	Nivel de triglicéridos
s6	Nivel de glucosa
🎯 Variable Objetivo
Valor continuo que representa la progresión de la enfermedad de diabetes
En este laboratorio se utiliza de dos formas:
Regresión: predicción directa del valor
Clasificación: transformación binaria (ej. target > 140)
⚙️ Consideraciones Técnicas
Dataset limpio (sin valores nulos)
Variables ya escaladas, lo que evita preprocessing adicional inicial
Ideal para:
Regresión lineal
Modelos de clasificación
Evaluación de métricas
Comparación de algoritmos
🧩 Estructura del Proyecto
1. 📥 Carga y exploración de datos
Uso de load_diabetes
Conversión a DataFrame con pandas
Exploración inicial
2. 📈 Regresión Lineal
Uso de BMI como predictor
Evaluación con MSE
3. 🔍 Regresión Logística
Clasificación binaria del target
4. 🌳 Árbol de Decisión
Modelo interpretable basado en reglas
5. 🌲 Random Forest
Ensemble con 100 árboles
Mejora de generalización
6. 📏 Evaluación de Modelos
Accuracy, Precision, Recall, F1-Score, MSE
7. 🔁 Validación Cruzada
K-Fold (k=5) para evaluar estabilidad
8. ⏱️ Series Temporales (ARIMA)
Simulación y predicción
9. 🔎 Descomposición de Series
Tendencia, estacionalidad y ruido con statsmodels
🛠️ Stack Tecnológico
Python 3.x
scikit-learn
pandas
numpy
matplotlib
statsmodels
🚀 Valor del Proyecto

Este repositorio permite:

Implementar un flujo completo de ML end-to-end
Comparar múltiples algoritmos sobre un mismo dataset
Entender el impacto de variables como BMI en la predicción
Aplicar buenas prácticas de validación
Extender análisis hacia forecasting
