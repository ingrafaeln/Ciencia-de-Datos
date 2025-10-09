# Aprendizaje Supervisado y No Supervisado

El aprendizaje automático es una rama de la inteligencia artificial que se centra en el estudio y construcción de sistemas capaces de aprender de los datos, identificar patrones y realizar decisiones con mínima intervención humana [1]. El aprendizaje automático se divide en dos grandes categorías: aprendizaje supervisado y aprendizaje no supervisado. 


En esta sección, se presentan ejemplos de aprendizaje supervisado y no supervisado utilizando la librería `scikit-learn` en Python. Dando una introducción al uso de algoritmos de clasificación, regresión y agrupamiento.

## Aprendizaje Supervisado

El aprendizaje supervisado es un tipo de aprendizaje automático en el que se proporcionan datos de entrada y salida etiquetados. El objetivo del aprendizaje supervisado es aprender una función que mapee los datos de entrada a los datos de salida. En otras palabras, el objetivo es aprender una función que pueda predecir la salida de nuevos datos de entrada. [1]

El aprendizaje supervisado se puede dividir en dos categorías: clasificación y regresión. En la clasificación, la salida es una etiqueta de clase, como "perro" o "gato". En la regresión, la salida es un valor numérico, como "peso" o "precio". [1]

### Modelos de Aprendizaje Supervisado

* **Algoritmos de Clasificación**
  * [Regresión Logística](https://numiqo.com/tutorial/logistic-regression)
  * [Árboles de Decisión](https://www.geeksforgeeks.org/machine-learning/decision-tree-introduction-example/)
  * [Máquinas de Soporte Vectorial](https://www.geeksforgeeks.org/machine-learning/support-vector-machine-algorithm/)
  * [K-Vecinos Más Cercanos](https://www.geeksforgeeks.org/machine-learning/k-nearest-neighbours/)
  * [Naive Bayes](https://www.geeksforgeeks.org/machine-learning/naive-bayes-classifiers/)
  * [XGBoost](https://www.geeksforgeeks.org/machine-learning/xgboost/)
  
* **Algoritmos de Regresión**
  * [Regresión Lineal](https://www.geeksforgeeks.org/machine-learning/ml-linear-regression/)
  * [Árboles de Decisión](https://www.geeksforgeeks.org/machine-learning/python-decision-tree-regression-using-sklearn/)
  * [Máquinas de Soporte Vectorial](https://www.geeksforgeeks.org/machine-learning/support-vector-regression-svr-using-linear-and-non-linear-kernels-in-scikit-learn/)
  * [K-Vecinos Más Cercanos](https://www.geeksforgeeks.org/machine-learning/k-nearest-neighbors-knn-regression-with-scikit-learn/)
  * [XGBoost](https://www.geeksforgeeks.org/machine-learning/xgboost-for-regression/)


## Aprendizaje No Supervisado

El aprendizaje no supervisado es un tipo de aprendizaje automático en el que se proporcionan datos de entrada sin etiquetar. El objetivo del aprendizaje no supervisado es modelar la estructura o distribución subyacente en los datos para aprender más sobre los datos. En otras palabras, el objetivo es aprender más sobre los datos sin una salida específica en mente. [1]

El aprendizaje no supervisado se puede dividir en dos categorías: agrupamiento y asociación. En el agrupamiento, el objetivo es descubrir grupos de puntos de datos similares. En la asociación, el objetivo es descubrir reglas que describan los datos. [1]

### Modelos de Aprendizaje No Supervisado

* **Algoritmos de Agrupamiento**
  
  * [K-Means](https://www.geeksforgeeks.org/machine-learning/k-means-clustering-introduction/)
  * [DBSCAN](https://www.geeksforgeeks.org/machine-learning/dbscan-clustering-in-ml-density-based-clustering/)

## Lista de Ejemplos

Los ejemplos presentados en esta sección son los siguientes:

- [Ejemplo 1: Aprendizaje Supervisado - Regresión](Ejemplo_1_unsurance_cost_regression.ipynb)
- [Ejemplo 2: Aprendizaje Supervisado - Clasificación](Ejemplo_2_WineQT_classification.ipynb)
- [Ejemplo 3: Aprendizaje No Supervisado](Ejemplo_3_mall_customers_clustering.ipynb)

## Referencias

[1]: Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems. O'Reilly Media.
