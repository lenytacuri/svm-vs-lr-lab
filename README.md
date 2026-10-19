# Laboratorio: SVM vs. regresión logística

Predicción de churn con SVM y regresión logística, visualización t-SNE y optimización de hiperparámetros con GridSearchCV y BayesSearchCV.

## Iniciar

```bash
cd ~/svm-vs-lr-lab
uv sync
uv run jupyter lab
```

Abre `SVM_vs_LR_Optimizacion.ipynb` y selecciona el kernel Python del proyecto. En VS Code selecciona `.venv/bin/python` como intérprete del cuaderno.

## Dependencias

- NumPy y pandas: preparación de datos.
- Matplotlib y seaborn: gráficos y mapas de calor.
- scikit-learn: t-SNE, escalado, SVM, regresión logística y validación cruzada.
- scikit-optimize: optimización bayesiana con BayesSearchCV.
- JupyterLab e ipykernel: ejecución local del cuaderno.

Se mantiene pandas en la serie 2.x por compatibilidad con el código original, que utiliza operaciones inplace sobre columnas. El archivo uv.lock fija las versiones instaladas.

El cuaderno se copió sin modificar ni resolver las actividades. Su carga de datos requiere conexión a Internet.
