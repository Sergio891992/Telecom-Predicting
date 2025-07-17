# Telecom Customer Churn Prediction

Este proyecto tiene como objetivo predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones utilizando técnicas de ciencia de datos y aprendizaje automático.

## 📊 Contenido del proyecto

- **Carga y exploración de datos:**  
  Se analiza un conjunto de datos que contiene información sobre clientes, servicios contratados, duración del contrato, métodos de pago, cargos mensuales, y la variable objetivo `Churn`.

- **Preprocesamiento:**  
  - Limpieza de datos (tratamiento de valores nulos y ajuste de tipos de datos).  
  - Codificación de variables categóricas utilizando `LabelEncoder` y `get_dummies`.  
  - Normalización de variables numéricas mediante `StandardScaler`.

- **Balanceo de clases:**  
  Se utiliza la técnica **SMOTE** para generar muestras sintéticas y abordar el desbalance de clases entre clientes que cancelan y los que no.

- **Modelado:**  
  Se entrenan y comparan los siguientes modelos de clasificación:
  - 🌲 **Random Forest Classifier**  
  - 📈 **XGBoost Classifier**  
  - 🧮 **Logistic Regression**

- **Evaluación de modelos:**  
  Se emplean las siguientes métricas para evaluar el rendimiento:
  - **Accuracy**  
  - **Precision**  
  - **Recall**  
  - **F1-score**  
  - **Matriz de confusión**

- **Selección del modelo final:**  
  Se selecciona el modelo con mejor desempeño general, priorizando la detección efectiva de clientes con alta probabilidad de cancelar el servicio.

## 🚀 Tecnologías utilizadas

- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook

## 📁 Archivo principal

- `Telecom Predicting.ipynb`: contiene todo el análisis, desde la exploración hasta el entrenamiento y evaluación de modelos.

## 📌 Objetivo final

Ayudar a empresas de telecomunicaciones a identificar clientes con alto riesgo de cancelación para implementar acciones preventivas y mejorar la retención.

---

📬 Si tienes sugerencias o deseas colaborar, no dudes en abrir un issue o un pull request.
