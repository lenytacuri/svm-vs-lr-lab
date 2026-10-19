## Resumen del laboratorio

En este laboratorio abordamos la **predicción del abandono de clientes (*churn*)** de una empresa de telecomunicaciones. Comparamos SVM y regresión logística, optimizamos sus hiperparámetros y evaluamos su capacidad para identificar clientes que abandonan el servicio, priorizando el **recall** ante el desbalance de clases.

## Índice de contenidos

1. **Preparación de los datos:** limpieza, tratamiento de valores faltantes, codificación y división estratificada en entrenamiento y test.
2. **Visualización con t-SNE:** estandarización mediante z-score y exploración del conjunto de entrenamiento en dos dimensiones.
3. **SVM con kernel RBF:** optimización de C y gamma mediante GridSearchCV y validación cruzada estratificada de 5 folds.
4. **Regresión logística polinomial:** incorporación de cuadrados e interacciones y optimización de la regularización.
5. **Optimización bayesiana:** búsqueda de hiperparámetros de SVM mediante BayesSearchCV.
6. **Evaluación y reflexión:** comparación de métricas, matrices de confusión, limitaciones de los datos y posibles mejoras.

## Objetivos de aprendizaje

- Preparar datos tabulares para un problema de clasificación con clases desbalanceadas.
- Aplicar t-SNE como herramienta de exploración visual.
- Utilizar pipelines para ajustar la imputación y el escalado dentro de la validación cruzada.
- Comparar búsqueda en cuadrícula y optimización bayesiana.
- Comprender el efecto de la regularización y la expansión polinomial.
- Interpretar recall, precisión, F1 y ROC AUC, relacionándolos con los errores del modelo.
- Plantear mejoras considerando el umbral de decisión, el desbalance y la información disponible en los datos.
