# **Actividad 04 - Usuarios de tarjeta de crédito**

## 🎯 **Objetivo**

En esta actividad, tu objetivo es utilizar el algoritmo K-means para segmentar usuarios de tarjetas de crédito en diferentes grupos basados en características como el monto de gasto mensual, frecuencia de uso, saldo promedio, y tipos de transacciones realizadas. Aplicarás K-means para identificar patrones en los datos y agrupar a los usuarios en segmentos que reflejen sus comportamientos y hábitos financieros. Evaluarás la eficacia de la segmentación analizando las características comunes dentro de cada grupo y cómo estos segmentos pueden ser utilizados para personalizar ofertas y estrategias de marketing dirigidas a diferentes tipos de usuarios. Reflexionarás sobre cómo la segmentación puede mejorar la gestión de cuentas y optimizar las estrategias de marketing para tarjetas de crédito.

---

## 📑 Instrucciones
1.	Utiliza el código de la [actividad 03](../Actividad-03/Actividad_03_K_means_Customer_Segmentation.ipynb) y modifícalo para hacer uso del dataset [Credit Card Customer Data](https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data)
2.	Revisa el conjunto de datos proporcionado, que contiene información sobre la actividad bancaria de los usuarios de tarjetas de crédito
3.	Asegúrate de entender las variables disponibles y cómo pueden utilizarse para segmentar a los usuarios en grupos significativos.
4.	Examina el conjunto de datos para identificar y manejar valores faltantes, duplicados y errores.
5.	Convierte las variables categóricas en variables numéricas si es necesario. Normaliza o estandariza las características para asegurar que todas tengan el mismo peso en el análisis de segmentación.
6.	Utiliza el método del codo para determinar el número óptimo de clústeres. Este método implica graficar la suma de los errores cuadráticos dentro del clúster (SSE) contra el número de clústeres y buscar el punto donde la reducción en SSE comienza a desacelerarse.
7.	Aplica el algoritmo K-means utilizando el número óptimo de clústeres determinado
8.	Asigna cada usuario a uno de los clústeres formados por el algoritmo.
9.	Analiza y describe cada clúster en términos de las características comunes y patrones encontrados. ¿Qué distingue a cada clúster de los demás?
10.	Presenta a la clase un reporte detallado que incluya: descripción del problema y objetivos, precedimientos de limpieza y pre procesamiento de datos, método del codo y número de clusters seleccionados, resultados de la segmentación K-means y análisis de clusters.
11.	Reflexión sobre cómo la segmentación puede ayudar a entender mejor el comportamiento de los usuarios de tarjetas de crédito y cómo esta información puede ser útil para estrategias de marketing o gestión de riesgos.

---

## ❓ **Momento de introspección**

Mientras trabajas en la segmentación de usuarios de tarjetas de crédito utilizando el algoritmo K-means, es importante que reflexiones sobre el impacto de la segmentación en la gestión de cuentas y en las estrategias de marketing. Pregúntate cómo agrupar a los usuarios en segmentos basados en sus comportamientos financieros puede revelar patrones útiles para ofrecer productos y servicios personalizados. Considera cómo la segmentación puede ayudarte a identificar grupos de usuarios con necesidades y preferencias similares, permitiéndote diseñar ofertas específicas y mejorar la satisfacción del cliente. Reflexiona también sobre la importancia de elegir el número adecuado de clústeres y cómo esta decisión afecta la interpretación de los resultados y las estrategias que puedes implementar. Piensa en cómo tus hallazgos pueden contribuir a una gestión más efectiva de las tarjetas de crédito y a la optimización de las campañas de marketing.


