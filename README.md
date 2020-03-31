## **Sistema de clasificación basado en Random Forest**

Para el diseño e implementación de un sistema capaz de detectar y clasificar los digitos escritos a mano y provistos por el dataset de Scikit Learn (sklearn.datasets.load_digits), se siguieron los siguientes pasos:

1. Carga del dataset "load_digits".
2. División de los datos en 70% elementos de entrenamiento, 30% de validación.
3. Construcción del modelo de clasificación Random Forest con 5 variaciones del número de arboles y características.
4. Validación del modelo y de posibles variables de respuesta/objetivo, mediante el análisis de curvas ROC para cada clase (digitos entre 0-9).
5. Gráfica de importancia de características para medir la variabilidad del modelo cuando se afectan las variables de entrada.
6. Comparación de resultados obtenidos.


Original file is located at
    https://colab.research.google.com/drive/1lbNbkbG4OLxQMqrWQhc4_VeQJAhT2UnN
