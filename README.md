# Breast Cancer Clasiffier en Python (Clasificador de Cáncer de Seno)

## Introducción

El presente proyecto muestra la comparación de la precisión de entrenamiento y prueba (Accuracy Train & Test) de los principales modelos de aprendizaje supervisados 
utilizados para un clasificador de cáncer de seno.

## Dataset

El dataset "Wisconsin Diagnostic Breast Cancer (WDBC)" fue obtenido desde: 
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Dicho dataset se compone de una columna "Diagnóstico" que será utilizada para la predicción del cáncer de seno: B = benigno, M = maligno. Y de 30
columnas adicionales de mediciones de parámetros cuantificados (numéricos) para la detección y evaluación de la enfermeadad.
En total se disponde de 568 registros en el dataset.

## Desarrollo

Los modelos de aprendizaje supervisados utilizados para el clasificador serán:
- Lineal
- KNN
- Árbol de Decisión
- y Random Forest.

Adicionalmente, para evitar el sobreajuste en los modelos de aprendizaje se utilizará el manejo de un parámetro de regularización (optimización), 
que permite identificar el mejor punto para una poda en el caso de los árboles de decisión.

## Conclusión

En base a esto se realizó una comparación de la precisión de entrenamiento y prueba (Accuracy Train & Test), llegando a la conclusión de que el
mejor modelo supervisado para la clasificación de cáncer de seno es el Random Forest con regularización que presenta un 100% de precisión de entrenamiento
y un 96.49% de precisión de prueba.
