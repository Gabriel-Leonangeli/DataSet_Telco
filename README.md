# 📊 Proyecto de Data Science: Predicción de Churn de Clientes

## 📌 Descripción

En este proyecto se desarrolla un modelo de Machine Learning para predecir si un cliente de una empresa de telecomunicaciones abandonará el servicio (churn).

El objetivo es aplicar un flujo completo de trabajo en Data Science, incluyendo limpieza de datos, transformación de variables, entrenamiento de modelos y evaluación de resultados.

---

## ⚙️ Proceso realizado

### 1. Limpieza de datos
- Conversión de la variable `TotalCharges` a formato numérico
- Reemplazo de valores vacíos por la mediana

### 2. Preprocesamiento
- Eliminación de variables irrelevantes como `customerID`
- Transformación de variables categóricas mediante One-Hot Encoding

### 3. Definición del problema
- Tipo: Clasificación binaria
- Target: `Churn` (Yes / No)

---

### 4. Modelos utilizados

Se entrenaron y compararon los siguientes modelos:

- Regresión Logística
- Random Forest
- Gradient Boosting

---

### 5. Evaluación del modelo

Se utilizaron métricas de clasificación:

- Accuracy
- Precision
- Recall
- F1 Score

Debido al desbalance del dataset, se priorizó el análisis de la métrica **recall**, ya que el objetivo es detectar clientes que abandonan el servicio.

---

## 📊 Resultados

- La regresión logística obtuvo el mejor equilibrio entre métricas
- Los modelos más complejos (Random Forest y Gradient Boosting) presentaron menor recall
- Se observó una mayor cantidad de falsos negativos en modelos más complejos

---

## 📈 Visualización

Se utilizaron matrices de confusión para comparar el rendimiento de los modelos y analizar sus errores.

---

## 🧠 Conclusiones

- La regresión logística resultó ser el modelo más adecuado para este problema
- Los modelos más complejos no siempre garantizan mejores resultados
- El análisis de métricas más allá de accuracy es clave en problemas desbalanceados

---

## 🚀 Posibles mejoras

- Ajuste de hiperparámetros
- Uso de técnicas para balancear datos (SMOTE, oversampling)
- Ajuste del threshold de clasificación
- Prueba de modelos más avanzados

---

## 📁 Estructura del proyecto

Proyecto_ParteIII_Gabriel.ipynb
data/
└── Telco-Customer-Churn.csv


---

## 🧠 Autor

Gabriel  
Proyecto realizado como práctica de Data Science
