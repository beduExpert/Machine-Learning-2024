# **Actividad 01 - Clasificación de sentimientos en mensajes de Twitter (X)**

## 🎯 **Objetivo**
El objetivo de esta Actividad es que evalúes y compares la eficacia de dos enfoques de redes neuronales recurrentes en la clasificación de sentimientos de mensajes de Twitter. Utilizarás redes neuronales recurrentes tradicionales y Gated Recurrent Units (GRU) para determinar cuál de los dos métodos ofrece un mejor rendimiento en términos de precisión y manejo de dependencias contextuales en los datos secuenciales. Deberás implementar ambos tipos de redes, entrenarlas con un conjunto de datos de Twitter y analizar sus resultados para identificar cuál modelo se adapta mejor a la tarea de clasificación de sentimientos. Considera factores como la calidad de las predicciones y la eficiencia del entrenamiento para obtener una comprensión más profunda de las fortalezas y limitaciones de cada técnica en el procesamiento de lenguaje natural.

---

## 📑 Instrucciones
**1. 	Abre el cuaderno proporcionado, el cual lo puedes encontrar en [Cuaderno](Actividad_01_SentimentClassification_Twitter.ipynb)**
**2.  Conecta Google Colab con tu cuenta de Kaggle**
**1.	Abre el cuaderno proporcionado, el cual lo puedes encontrar en [Cuaderno](Actividad_01_SentimentClassification_Twitter.ipynb)**
**2.  Conecta Google Colab con tu cuenta de Kaggle**
**3.	Descarga del Dataset en Google Colab desde [Link](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis/data)**
**4.	Preparación del entorno**
a.	Asegúrate de tener acceso a un entorno de desarrollo adecuado con las librerías necesarias instaladas, como PyTorch para la implementación de redes neuronales.
b.	Configura tu entorno de trabajo con las herramientas necesarias para procesar datos y construir modelos.
**5.	Obtención y Preprocesamiento de Datos**
a.	Descarga el conjunto de datos de mensajes de Twitter que será utilizado para la clasificación de sentimientos. Asegúrate de que el dataset esté en un formato adecuado (por ejemplo, CSV o JSON) y contenga etiquetas de sentimiento.
b.	Realiza el preprocesamiento de los datos, que incluye la limpieza de texto (eliminación de URLs, menciones, y caracteres especiales), tokenización y conversión de texto a secuencias numéricas utilizando técnicas de vectorización (como Tokenizer en Keras o CountVectorizer en Scikit-learn).
**6.	Construcción del Modelo**
a.	Implementa una red neuronal recurrente simple utilizando una capa de RNN. Ajusta los parámetros de la red, como el número de unidades de la capa recurrente y la función de activación.
b.	Compila y entrena el modelo con el conjunto de datos de entrenamiento. Utiliza funciones de pérdida adecuadas para la clasificación de sentimientos y optimizadores como Adam o RMSprop.
c.	Implementa un modelo utilizando una capa GRU. Configura los parámetros de la capa GRU y compila el modelo de manera similar al modelo RNN.
d.	Entrena el modelo GRU con el mismo conjunto de datos de entrenamiento y ajusta los hiperparámetros según sea necesario.
**7.	Evaluación del Modelo**
a.	Evalúa ambos modelos utilizando el conjunto de datos de prueba. Calcula métricas de rendimiento como precisión, recall, F1-score, exactitud y matriz de confusión para cada modelo.
b.	Realiza una comparación de los resultados obtenidos de ambos modelos. Examina cómo cada uno maneja la clasificación de sentimientos y determina cuál ofrece un mejor rendimiento.
**8.	Análisis y Discusión**
a.	Documenta los resultados de la evaluación de ambos modelos en un informe.
b.	Discute las ventajas y desventajas de cada enfoque en la tarea de clasificación de sentimientos. Considera aspectos como la calidad de las predicciones, la eficiencia del entrenamiento y la capacidad de manejar dependencias contextuales.
c.	Proporciona una explicación detallada de cuál modelo consideras más adecuado para esta tarea y justifica tu elección basada en los resultados obtenidos.
**9.	Entrega y Presentación**
a.	Prepara un informe con los detalles del preprocesamiento de datos, la arquitectura de los modelos, los resultados de la evaluación y el análisis comparativo.
b.	Adjunta cualquier código fuente relevante y gráficos de rendimiento en el informe.
c.	Presenta tu informe al resto de la clase para obtener retroalimentación por parte de tus compañeros y del instructor



---

## ❓ **Momento de introspección**

Ahora que has completado la actividad de clasificación de sentimientos utilizando redes neuronales recurrentes y Gated Recurrent Units (GRU), tómate un momento para reflexionar sobre cómo puedes aplicar lo que has aprendido a problemas reales y a tu futuro profesional. Considera las siguientes preguntas para guiar tu reflexión:

**¿Cómo puedes aplicar los conceptos de redes neuronales recurrentes (RNN) y GRU en problemas reales?**
Piensa en áreas específicas, como el análisis de sentimientos en redes sociales, la predicción de series temporales o el procesamiento de lenguaje natural. ¿Qué otras aplicaciones prácticas podrían beneficiarse de estos métodos?

**¿Qué desafíos encontraste al trabajar con RNN y GRU?**
Reflexiona sobre los problemas que enfrentaste durante el preprocesamiento de datos, la construcción y el entrenamiento de modelos. ¿Cómo podrías superar estos desafíos en futuros proyectos?

**¿Cómo afectó la complejidad de las arquitecturas RNN y GRU a los resultados de tus modelos?**
Analiza la diferencia en el rendimiento entre el modelo RNN tradicional y el modelo GRU. ¿Qué aspectos de cada arquitectura impactaron la precisión y eficiencia de los modelos?

**¿Qué aprendizajes clave puedes extraer de la comparación entre RNN y GRU?**
Considera cómo la elección de la arquitectura de red afecta la capacidad del modelo para manejar datos secuenciales y cómo esta elección influye en la calidad de las predicciones.

**¿Cómo puedes mejorar tu enfoque al trabajar con redes neuronales en el futuro?**
Reflexiona sobre las prácticas y estrategias que utilizaste en esta actividad. ¿Qué mejoras podrías implementar para optimizar el rendimiento de tus modelos y la eficiencia del proceso de entrenamiento?

**¿Qué habilidades y conocimientos adquiridos en esta actividad pueden ser útiles para tu desarrollo profesional?**
Piensa en cómo las habilidades adquiridas al trabajar con RNN y GRU pueden aplicarse a proyectos futuros o en el ámbito profesional. ¿Cómo puedes aprovechar estas competencias para resolver problemas en tu campo de estudio o en tu carrera?

**¿Cómo puedes integrar el aprendizaje sobre redes neuronales recurrentes en otros proyectos o áreas de investigación?**
Considera cómo los conceptos de redes neuronales recurrentes pueden ser relevantes en otras áreas de investigación o proyectos interdisciplinarios. ¿Qué nuevas oportunidades podrían surgir al aplicar estos conocimientos en diferentes contextos?

Dedica unos minutos a responder estas preguntas en tu cuaderno de reflexiones o en un documento personal. Este proceso de introspección te ayudará a consolidar tu comprensión y a planificar cómo puedes aplicar lo aprendido en futuras actividades académicas o profesionales.
tado una red compleja como VGG16, ¿qué otros modelos o técnicas te gustaría investigar? ¿Qué áreas del aprendizaje profundo captaron más tu interés?






