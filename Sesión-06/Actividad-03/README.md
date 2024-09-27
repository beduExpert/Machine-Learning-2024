# **Actividad 03 - Predicción del precio del Oro**

## 🎯 **Objetivo**
El objetivo de esta actividad es que apliques redes neuronales LSTM (Long Short-Term Memory) para la predicción del precio del oro, utilizando datos históricos de series de tiempo. A través de este ejercicio, desarrollarás habilidades en el preprocesamiento de datos financieros, la implementación y ajuste de modelos LSTM, y la visualización de resultados mediante comparaciones entre los valores predichos y los reales. Además, se busca que adquieras una comprensión profunda de cómo las redes neuronales recurrentes pueden capturar patrones temporales complejos en datos financieros, mejorando tu capacidad para resolver problemas de predicción en escenarios del mundo real.

---

## 📑 Instrucciones
1. Con la ayuda del profesor, corre el siguiente [Programa](Actividad_03_Predicción_precio_oro.ipynb)
2. Descarga el dataset que utilizarás del siguiente [enlace](https://www.kaggle.com/datasets/farzadnekouei/gold-price-10-years-20132023)
3. Pon mucha atención a la explicación del profesor en la ejecución de cada línea de código.
4. Realiza tus observaciones y anotaciones para futuras referencias
5. Normaliza los datos para que se encuentren en un rango entre 0 y 1, lo cual es esencial para mejorar el rendimiento del modelo LSTM.
6. Divide los datos en un conjunto de entrenamiento y uno de prueba.
7. Utiliza una librería como TensorFlow o Keras para implementar la red LSTM.
8. Define las capas del modelo, comenzando con una o más capas LSTM y añadiendo capas densas al final.
9. Entrena el modelo utilizando el conjunto de datos de entrenamiento.
10. Ajusta hiperparámetros como el número de épocas y el tamaño de batch, buscando un buen equilibrio entre precisión y tiempo de entrenamiento.
11. Evalúa el modelo con el conjunto de prueba para medir su desempeño.
12. Grafica las predicciones del modelo junto con los precios reales del oro para visualizar el rendimiento.
13. Incluye gráficos que muestren el comportamiento del precio del oro y cómo las predicciones del modelo se alinean con los valores reales.
14. Escribe un reporte técnico que documente el proceso completo, desde la obtención y preprocesamiento de los datos hasta la implementación del modelo y los resultados obtenidos.
15. Analiza los errores en las predicciones y propone posibles mejoras para el modelo en futuras iteraciones.




---

## ❓ **Momento de introspección**

Tómate un momento para reflexionar sobre tu proceso en esta actividad. A medida que avanzas en la implementación de la red LSTM y en el análisis de los resultados, pregúntate:

1. ¿Cómo ha sido tu experiencia al trabajar con datos de series de tiempo?
2. ¿Te sentiste cómodo/a con el preprocesamiento y la estructura de los datos?
3. ¿Qué dificultades enfrentaste al normalizar y preparar los datos?
4. ¿Comprendiste el funcionamiento de las redes recurrentes y cómo se aplican a los datos temporales?
5. ¿Qué consideraciones tuviste en cuenta al seleccionar los hiperparámetros (como el número de épocas y el tamaño del batch)?
6. ¿Las predicciones fueron lo que esperabas? ¿Qué tan cerca estuvo tu modelo de los valores reales?
7. ¿Cómo interpretas las diferencias entre las predicciones y los valores reales? ¿A qué factores crees que se deben?
8. ¿Cómo ha cambiado tu comprensión sobre la importancia de capturar patrones temporales en datos históricos?
9. ¿Qué nuevas habilidades o conceptos sientes que adquiriste al trabajar con modelos LSTM?
10. ¿Qué harías diferente si tuvieras más tiempo o recursos?
11. ¿Qué cambios harías en el modelo o en el preprocesamiento para mejorar la precisión de las predicciones?

Responder estas preguntas te ayudará a profundizar en tu aprendizaje y a reconocer las áreas en las que podrías seguir mejorando en futuros proyectos.





