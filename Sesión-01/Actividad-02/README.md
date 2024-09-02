# **Actividad 02 - Análisis crítico de modelos de machine learning**

# 🎯 **Objetivo**
En esta actividad, aplicarás tus conocimientos sobre conjuntos de datos, sobreajuste, regularización y métricas de evaluación a través del análisis crítico de estudios de caso donde se presentan diferentes modelos de Machine Learning.

---

## 📑 Instrucciones

1.	Lee cuidadosamente el caso de estudio mostrado abajo
2.	Evalúa la estrategia utilizada para dividir los datos en entrenamiento, validación y prueba, y contesta las siguientes preguntas:
   - ¿Es adecuada para el problema?
   - ¿Podría mejorarse?
3.	Analiza si el modelo muestra señales de sobreajuste. Contesta las siguientes preguntas:
    - Si se presenta sobre ajuste, ¿qué acciones se deberían tomar?
    - En caso de que no se presente sobre ajuste, argumenta tu respuesta
4.	Interpreta las métricas de evaluación presentadas y discute qué nos dicen sobre el rendimiento del modelo. 
   - ¿Es el modelo suficientemente robusto para ser aplicado en el mundo real?
5.	Elabora una propuesta de mejora para el modelo presentado. Estas mejoras pueden incluir ajustes en la división de los datos, cambios en las técnicas de regularización, o sugerencias para utilizar otras métricas de evaluación.
6.	Presentar tus análisis y propuestas de mejora en una breve exposición (10 minutos). Deberás argumentar por qué las mejoras propuestas podrían llevar a un mejor desempeño del modelo.

 ---
## 📑 Caso de Estudio: Predicción de Precios de Viviendas 
**Problema** <br />
Una empresa inmobiliaria desea predecir los precios de las viviendas en una gran ciudad utilizando un modelo de Machine Learning. El objetivo es desarrollar un modelo que pueda estimar el precio de una vivienda basada en diversas características como la ubicación, el tamaño (en metros cuadrados), el número de habitaciones, el año de construcción, y la proximidad a servicios públicos. 
 
Objetivo del Modelo
El modelo busca minimizar la diferencia entre el precio real de las viviendas y las predicciones del modelo, logrando la mayor precisión posible para ayudar a la empresa a realizar evaluaciones de precios más rápidas y precisas, lo cual optimizará sus estrategias de compra y venta.

División de Conjuntos de Datos
Para entrenar y evaluar el modelo, los datos se dividieron de la siguiente manera: 
•	Conjunto de Entrenamiento (50%): Se usó para entrenar el modelo, es decir, para que el algoritmo aprenda las relaciones entre las características de las viviendas y sus precios. 
•	Conjunto de Validación (25%): Este subconjunto se utilizó para ajustar los hiper parámetros del modelo y prevenir sobreajuste. Fue crucial para elegir el nivel adecuado de regularización. 
•	Conjunto de Prueba (25%): Este conjunto se reservó exclusivamente para evaluar el rendimiento final del modelo, asegurando que los resultados sean representativos y no sesgados por el proceso de ajuste.

Resultados de Diferentes Experimentos
Precisión en Validación: 93%
Precisión en Prueba: 72%



