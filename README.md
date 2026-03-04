# 📊 Telecom X - Parte 2: Predicción de Cancelación de Clientes (Churn)

## 🚀 Abrir Proyecto

[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab&logoColor=white&style=for-the-badge)](https://colab.research.google.com/drive/1sWhZUxDztLomxg2nEfTWwUuOpO8fYBg5#scrollTo=NnCyTJMGvrnm)) 
[![Trello Board](https://img.shields.io/badge/View%20Project-Trello-0052CC?logo=trello&logoColor=white&style=for-the-badge)](https://trello.com/b/Vq1Dtqny/telecomxparte2aula-latam-oracle)


## 📌 Descripción

Este proyecto corresponde a la Parte 2 del Challenge Telecom X, enfocado en el desarrollo de modelos de Machine Learning para predecir la cancelación de clientes (churn).

A partir de un dataset previamente limpiado en la Parte 1, se realizó la preparación de datos, análisis de variables relevantes, entrenamiento de modelos de clasificación y evaluación de su desempeño.

El objetivo fue identificar los factores que influyen en la baja de clientes y generar información útil para la toma de decisiones estratégicas.

---

## 🛠️ Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab  

---

## ⚙️ Proceso del Proyecto

### 1️⃣ Preparación de Datos
- Eliminación de variables irrelevantes.
- Codificación de variables categóricas (One-Hot Encoding).
- Escalado de variables numéricas.
- Separación de variable objetivo (Churn).
- Análisis de proporción de clases.

### 2️⃣ Análisis y Selección de Variables
- Matriz de correlación.
- Identificación de variables con mayor relación con el churn.
- Análisis de antigüedad (Tenure) y cargos mensuales.

### 3️⃣ Modelado Predictivo
Se entrenaron dos modelos de clasificación:

- Regresión Logística
- Random Forest

Se evaluaron utilizando:
- Accuracy  
- Precisión  
- Recall  
- F1-score  
- Matriz de Confusión  

La Regresión Logística presentó el mejor equilibrio entre métricas y permitió una interpretación clara de los factores influyentes.

---

## 📈 Principales Hallazgos

Los clientes con mayor probabilidad de cancelar el servicio suelen:

- Tener contratos mensuales.
- Presentar baja antigüedad.
- Tener cargos mensuales elevados.
- Contar con servicio de internet por fibra óptica.

Estas variables fueron determinantes en el comportamiento del modelo predictivo.

---

## 🎯 Conclusión

El análisis permitió identificar qué factores influyen en la cancelación de clientes y desarrollar un modelo que ayuda a anticipar esas bajas antes de que ocurran.

La Regresión Logística fue el modelo más adecuado, ya que combinó buen rendimiento con facilidad de interpretación, permitiendo generar información útil para aplicar estrategias de retención y reducir la pérdida de clientes.

---

## 💼 Autor

Maria Barbaran - Proyecto educativo de análisis de datos con Python realizado como parte del programa Data Science ONE (G9) de Alura LATAM.
