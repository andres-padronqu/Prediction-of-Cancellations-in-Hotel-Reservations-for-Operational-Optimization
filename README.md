# Prediction-of-Cancellations-in-Hotel-Reservations-for-Operational-Optimization

Este proyecto busca **predecir las cancelaciones de reservas de hotel** con el fin de mejorar la **optimización operativa** en la industria hotelera.  
A través de técnicas de **Machine Learning**, se analizan los factores clave que influyen en las cancelaciones y se construyen modelos que permiten anticiparlas y tomar mejores decisiones estratégicas.

---

## Objetivos
- Identificar las variables más relevantes que determinan la probabilidad de cancelación.
- Construir un modelo de predicción de cancelaciones de reservas.
- Evaluar diferentes enfoques de modelado (Logit, Probit, LASSO, árboles, etc.).
- Proveer **insights accionables** para la industria hotelera y optimizar la gestión de recursos.

---

## Metodología
1. **Análisis exploratorio de datos (EDA)**  
   - Distribución de variables  
   - Correlaciones clave  
   - Visualizaciones  

2. **Preprocesamiento**  
   - Limpieza de datos  
   - Codificación de variables categóricas  
   - Balanceo de clases (SMOTE/ROSE)  

3. **Modelado**  
   - Regresión logística (Logit / Probit)  
   - LASSO / Ridge  
   - Árboles de decisión y Random Forests  

4. **Evaluación**  
   - ROC AUC, Precision-Recall, F1-Score  
   - Matriz de confusión  
   - Curvas de validación y aprendizaje  

---

## Resultados esperados
- Un modelo predictivo capaz de detectar cancelaciones con alta precisión.  
- Identificación de las variables más influyentes (ej. `lead_time`, `deposit_type`, `hotel`).  
- Visualizaciones claras para interpretar el comportamiento de las reservas.  

---

## Próximos pasos
- Optimizar hiperparámetros de modelos.  
- Comparar performance entre modelos lineales y de ensamble.  
- Desarrollar una interfaz simple para que usuarios no técnicos puedan usar el predictor.  

---
