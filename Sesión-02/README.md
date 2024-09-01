🏠 [**Inicio**](../README.md) ➡️ / 📖 `Sesión 01`

<div align="center">
    <img src="../BEDU.JPG" alt="Sesion_01">
</div>

## 🎯 Objetivos

⚒️ El objetivo de esta sesión es que desarrolles un entendimiento sólido de los algoritmos de árboles de decisión y K-means, comprendiendo sus fundamentos, aplicaciones y diferencias clave. Aprenderás a utilizar los árboles de decisión para resolver problemas de clasificación y regresión, aprovechando su capacidad para modelar decisiones de manera clara y explicable. Además, te familiarizarás con el uso del algoritmo K-means para la agrupación de datos no etiquetados, permitiéndote identificar patrones ocultos y estructuras dentro de los datos. Al final de la sesión, serás capaz de aplicar ambos algoritmos a diferentes conjuntos de datos, interpretar sus resultados, y seleccionar el método adecuado según las características y necesidades del problema que enfrentes.


---

📘 Material del prework:
En el prework podrás encontrar la parte teórica que utilizaremos para realizar los ejercicios de esta sesión. 
🔥¡Vamos a comenzar!🔥

---

## 📂 Temas de la sesión...


### 📖 Introducción a los árboles de decisión

Los árboles de decisión son una de las herramientas más útiles en machine learning debido a su simplicidad y facilidad de interpretación. Son especialmente efectivos para problemas de clasificación y regresión, ya que te permiten dividir los datos en subconjuntos más pequeños y homogéneos basados en características específicas. En este subtema, explorarás los conceptos básicos y los elementos que componen los árboles de decisión, además de conocer sus ventajas, desventajas y aplicaciones prácticas.

---

### 📖 Construcción de un árbol de decisión

En este subtema, te sumergirás en el proceso de construcción de un árbol de decisión. Aprenderás cómo elegir las características más importantes y cómo decidir dónde dividir los datos para crear un modelo efectivo. También descubrirás diferentes algoritmos utilizados para construir árboles de decisión, como el algoritmo CART (Classification and Regression Trees) y cómo estos algoritmos manejan la división de los datos en función de métricas de impureza.

---

### 📖 Introducción al algoritmo K-means

El algoritmo K-means es uno de los algoritmos de agrupamiento más utilizados en el aprendizaje no supervisado. Su objetivo principal es dividir un conjunto de datos en k grupos o clusters distintos. Cada cluster está formado por datos que comparten características similares, mientras que los datos de diferentes clusters son lo más distintos posible. Este método es particularmente útil cuando necesitas descubrir patrones o estructuras ocultas en datos sin etiquetar.

### 📖 Algoritmo K-means

El algoritmo K-means consiste en los siguientes pasos:
1. Inicialización: Primero, seleccionas k puntos aleatorios del conjunto de datos. Estos puntos iniciales actúan como los centroides de los clusters. Es crucial cómo eliges estos centroides iniciales, ya que afectará el resultado final del algoritmo. En la Fig. 3 podemos observar estos puntos en color rojo.

2.	Asignación de Clusters: Para cada punto de datos en el conjunto, calculas la distancia entre ese punto y cada uno de los centroides. Luego, asignas el punto al cluster cuyo centroide esté más cerca. La distancia más comúnmente utilizada es la distancia euclidiana, pero otras métricas como la distancia Manhattan o la distancia coseno también pueden ser aplicadas dependiendo de la naturaleza del problema.

3.	Recalcular Centroides: Una vez que todos los puntos han sido asignados a un cluster, recalculas los centroides de cada cluster. Esto se hace tomando el promedio de todos los puntos de datos que pertenecen al cluster.

4.	Repetir hasta Convergencia: Los pasos de asignación de clusters y recalculo de centroides se repiten hasta que los centroides ya no cambien significativamente o hasta que se alcance un número máximo de iteraciones. Este punto de estabilidad se conoce como "convergencia". En la Fig. 4 se observa que cada uno de los tres centroides se ha movido hacia cada uno de los clusters de tal manera que la distancia promedio es la mínima.


---

### ✏️ Actividades

#### 📕 **[Actividad 01: Identificación del tipo de aprendizaje](/Sesión-01/Actividad-01/README.md)**
#### 📕 **[Actividad 02: Análisis crítico de modelos de machine learning](/Sesión-01/Actividad-02/README.md)**

---

⬅️ [**Anterior**](../README.md) | [**Siguiente**](../Sesion-02/README.md)➡️
