# <h1 align=center> **PROYECTO INDIVIDUAL** </h1>

# <h1 align=center>**`Data Scientist`**</h1>

<p align="center">
<img src=".\_src\assets\machine_learning.jpg"  height=350>
</p>
  

<hr>  

# Descripción del problema
​
El proyecto consiste en lograr estimar adecuadamente el valor de una propiedad dentro del rubro de una inmobiliaria en los Estados de Unidos utilizando ciertas metricas para poder medir el perfomance de los modelos de machine learning creados, y de esta manera  entender si es una buena oportunidad, ya sea de compra o de venta, a traves de la eleccion de los modelos.

​Es el caso que se proponen  la realizacion de dos modelos:
​
1. Implementar un `modelo de clasificación con aprendizaje supervisado` que permita clasificar el precio de las propiedades en venta, el objetivo es predecir si una propiedad pertenece a la categoría de precios bajos (low <= 999). 
​
2. Implementar un `modelo de clasificación con aprendizaje no supervisado`, utilizando clustering que agrupe las propiedades por segun las **3 categorias** a las que pueden pertenecer. Para ello, solo usaran el dataset de test provisto, eliminando previamente las caracteristicas que presenten nulos.
​
​
# Métrica a utilizar
​
Como método de evaluación del desempeño, dependerá del modelo que usted decida implementar.
​
1. Para el **modelo de aprendizaje supervisado**, se utilizará la métrica `Accuracy` para las propiedades de precio bajo (low):

$$ Recall=\frac{TP+ TN}{TP+TN+FP+FN}$$

​
Donde $TP$ son los verdaderos positivos, $FP$ los falsos positivos, $FN$ los falsos negativos y $FN$ los falsos negativos. </br>
​
2. Para el **modelo de aprendizaje no supervisado**, se utilizará la métrica `Silhouette score`:

$$ Silhouette=\frac{b_i-a_i}{max(b_i,a_i)}$$

Dónde $b_i$ es la distancia promedio al grupo más cercano desde el punto i, $a_i$ es la distancia promedio a todos los demás puntos del clúster al que pertenece el punto i. 




# Requerimientos

Todo los pautas generales sobre el proyecto se encuentran en el achivo <a href="https://github.com/aylinv94/Datathon/blob/main/Consulta.md">Consulta.md</a> </strong> del repositorio. Cabe destacar, que en vista del peso excesivo de los dataset de origen (train.parquet y test.parquet) se tuvieron que almecenar en un <a href="https://github.com/aylinv94/Datathon/blob/main/Consulta.md">drive</a> </strong> para una posterior visualizacion y analisis
