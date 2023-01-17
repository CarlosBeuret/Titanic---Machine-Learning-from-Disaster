<h1 align=center>Proyecto: Titanic - Machine Learning from Disaster</h1>



<h2 align=center>Introducción al proyecto.</h2>



Para la realización del proyecto ingresamos a la competencia de Kaggle denominada "Proyecto: Titanic - Machine Learning from Disaster" y descargamos dos archivos .csv. 

El objetivo es que mediante el analisis de los mismos y la implementación de conocimientos de Machine Learning podamos generar un modelo con la capacidad predecir con el mayor grado de exactitud posible la supervivencia o no de diferentes personas ante el hundimiento del Titanic.

<h2 align=center>Análisis Exploratorio de Datos (EDA)</h2>

Lo primero que cabe mencionar es que nuestros datos provienen de dos archivos diferentes, uno para entrenamiento y otro para testeo. Estos se encuentran disponibles en la carpeta Datasets.

Lo relativo al analisis exploratorio  lo podemos encontrar en el archivo EDA.ipynb. Se eligió utilizar Jupyter Notebook por que nos permitió hacer el analisis mas sencillo y segmentado.
El primer paso fue ingestar los achivos,  analizarlos y luego se los imcorporo a sus respectivos dataframe.

Luego, se analizó el contenido de cada uno de ellos en busca duplicados, valores faltantes, se buscaron errores de carga y en los tipos de los datos. También, se determinó cuales serían las transformaciones necesarias para poder realizar un adecuado entrenamiento de los modelos de machine learning.

Por último, se analizaron las correlaciones entre las columnas, su importancia y cual información se utilizaría para entrenar a los modelos.

<h2 align=center>Creación de pipelines, prueba de modelos y optimizacón de hiperparámetros. </h2>
Por otro lado, y con el fin de automatizar y simplificar los procesos se ultilizó la librería pipelines. Asi se logro realizar las tareas de transformación de datos y entrenamiento de los modelos de una manera muy sencilla, práctica y fácilmente reutilizable. Este proceso lo encontramos en el archivo main.ipynb.


También se utilizó Gridsearch para orientarnos y lograr una adecuada optimización de hiperparametros.

En cuanto al proyecto en general, principalmente se utilizo la librería Scikit-Learn y se probaron los modelos SVC, DecisionTreeClassifier,KNeighborsClassifier, BaggingClassifier, RandomForestClassifier y XGBClassifier. Las predicciones de los modelos mas prometedoras se guardaron en la carpeta resultados.


El mejor resultado obtenido fue el de RandomForestClassifier con un escore de 0.79186.


## **Herramientas utilizadas.**

* Vs Code.
* Python( pandas, numpy, Sklearn, pipelines).
* Jupyter Notebook.

Kaggle Account User Name: carlosbeuret 
