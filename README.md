# 🍷 Predicción de calidad de vinos con Machine Learning

Este proyecto tiene como objetivo construir un modelo predictivo que estime la calidad del vino a partir de características fisicoquímicas. Se trabaja con el conocido dataset de vinos tintos de la UCI Machine Learning Repository.

## 🎯 Objetivo

Predecir la calidad del vino (variable categórica) usando técnicas de clasificación de machine learning como regresión logística y árboles de decisión.

## 📚 Dataset

Se utiliza el dataset de vinos tintos (`winequality-red.csv`), que incluye variables como:

- Acidez fija / volátil
- Ácido cítrico
- Azúcares residuales
- pH
- Sulfatos
- Alcohol
- Entre otras...

La variable objetivo es `quality`, que representa la calidad del vino según una escala del 0 al 10.

## 🔧 Proceso del proyecto

1. **Carga y exploración de los datos**  
   Se analiza la distribución de las variables y la correlación entre ellas.

2. **Preprocesamiento**  
   - División del dataset en variables independientes y dependientes.
   - Escalado de datos con `StandardScaler`.
   - Separación en conjuntos de entrenamiento y prueba.

3. **Modelado**  
   - Entrenamiento de un modelo de **Regresión Logística**.
   - Entrenamiento de un **Árbol de Decisión**.

4. **Evaluación**  
   - Métricas utilizadas: Accuracy, Matriz de Confusión, Reporte de Clasificación.
   - Comparación entre modelos para determinar cuál predice mejor la calidad del vino.
