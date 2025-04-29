# Análisis de Sentimiento Financiero con Transformers y Ensamble

Este repositorio contiene un proyecto en Python para realizar análisis de sentimiento sobre textos del ámbito financiero. Emplea la librería Hugging Face Transformers y el conjunto de utilidades datasets para:

Cargar y procesar un CSV de datos etiquetados con clases de sentimiento.

Configurar pipelines de distintos modelos pre-entrenados (por ejemplo, FinancialBERT), ejecutándolos en conjunto para obtener un ensamble de predicciones basado en la suma de probabilidades.

Evaluar la calidad de las predicciones mediante métricas clave: accuracy, F1-macro, matriz de confusión y reporte de clasificación.

Visualizar los resultados con gráficos generados en Matplotlib:

Matriz de confusión

Barras de Precision, Recall y F1-Score por clase

F2-Score por clase
