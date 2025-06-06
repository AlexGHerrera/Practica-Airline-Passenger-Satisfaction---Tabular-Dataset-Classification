# Practica-Airline-Passenger-Satisfaction---Tabular-Dataset-Classification
Predicción de satisfacción de clientes a partir de datos tabulares. Incluye EDA, preprocesado, modelos clásicos (Sklearn) y una red neuronal (Keras), con evaluación detallada de métricas y thresholds.

# ✈️ Clasificación de Satisfacción de Pasajeros Aéreos

Este proyecto es parte del Bootcamp de Data Science en [Hack a Boss](https://www.hackaboss.com/). Aquí se desarrolla un modelo de clasificación para predecir si un pasajero está satisfecho o no, en base a múltiples variables relacionadas con su experiencia de vuelo.

---

## 📁 Archivo principal

- `02. Airline Passenger Satisfaction - Tabular Dataset Classification.ipynb`: Notebook completo con análisis, visualizaciones, entrenamiento de modelos y evaluación de resultados.

---

## 🧠 Objetivo

Predecir la satisfacción de los pasajeros (`Satisfied` o `Neutral/Dissatisfied`) a partir de características como clase de vuelo, servicio de abordo, tiempo de espera, comodidad del asiento, entre otras.

---

## 🧪 Proceso de trabajo

1. **Exploración y limpieza de datos**  
   - Detección y tratamiento de valores nulos  
   - Codificación categórica  
   - Normalización y escalado

2. **Visualización de datos**  
   - Análisis de correlaciones  
   - Distribución de variables  
   - Comparativas entre grupos de pasajeros

3. **Modelado y evaluación**  
   - Modelos utilizados:
     - Regresores logísticos
     - Árboles de decisión
     - Random Forest
     - KNN
     - Redes Neuronales (Keras)
   - Métricas evaluadas:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
     - ROC-AUC

4. **Optimización de resultados**  
   - Ajuste de thresholds  
   - EarlyStopping en redes neuronales  
   - Comparación visual de modelos

---

## 📊 Resultados destacados

- Se obtiene una red neuronal ajustada con métricas comparables (o superiores) a modelos clásicos.
- Se identifica un threshold óptimo para mejorar la precisión del modelo en función de los objetivos del negocio.

---

## 💡 Reflexiones

Este tipo de proyectos son esenciales para comprender los flujos reales de Machine Learning: desde el análisis exploratorio hasta la evaluación final. Además, permite practicar buenas prácticas como modularización, visualización eficaz y documentación.

---

## 🔧 Herramientas utilizadas

- Python 🐍  
- Pandas, NumPy  
- Scikit-Learn  
- Seaborn & Matplotlib  
- TensorFlow / Keras  
- Jupyter Notebook

---

## 📌 Notas

📎 Este trabajo se ha realizado como parte de una práctica académica. Los datos utilizados provienen de un dataset público (por ejemplo, [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)) y no representan clientes reales.

---

## 👨‍💻 Autor

**Alex Guerra**  
Bootcamp Data Science - Hack a Boss  
[LinkedIn](https://www.linkedin.com/in/alejandro-guerra-herrera-a86053115/)
