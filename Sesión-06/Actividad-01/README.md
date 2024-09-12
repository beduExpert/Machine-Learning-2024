# **Actividad 01 - Clasificación de Imágenes con CNN**

## 🎯 **Objetivo**
El objetivo de esta Actividad es que evalúes y compares la eficacia de dos enfoques de redes neuronales recurrentes en la clasificación de sentimientos de mensajes de Twitter. Utilizarás redes neuronales recurrentes tradicionales y Gated Recurrent Units (GRU) para determinar cuál de los dos métodos ofrece un mejor rendimiento en términos de precisión y manejo de dependencias contextuales en los datos secuenciales. Deberás implementar ambos tipos de redes, entrenarlas con un conjunto de datos de Twitter y analizar sus resultados para identificar cuál modelo se adapta mejor a la tarea de clasificación de sentimientos. Considera factores como la calidad de las predicciones y la eficiencia del entrenamiento para obtener una comprensión más profunda de las fortalezas y limitaciones de cada técnica en el procesamiento de lenguaje natural.

---

## 📑 Instrucciones
1.	Abre el cuaderno proporcionado, el cual lo puedes encontrar en [Cuaderno](https://github.com/beduExpert/Machine-Learning-2024/blob/e9088f91f47e6dd0f309f74a0648aa0f6bfe490f/Sesi%C3%B3n-05/Actividad-01/Actividad%2001%20-%20VGG16%20sobre%20CIFAR10.ipynb)
2.  Conecta Google Colab con tu cuenta de Kaggle
3.	Descarga del Dataset CIFAR10 en Google Colab desde [Link](https://www.kaggle.com/datasets/swaroopkml/cifar10-pngs-in-folders)
4.	Divide el dataset en conjuntos de entrenamiento y prueba.
5.	Asegúrate de normalizar las imágenes utilizando ``` torchvision.transforms ```  para que los valores de píxeles estén en un rango adecuado.
6.	Importa la arquitectura VGG16 desde ```torchvision.models```.
7.	Carga el modelo preentrenado y reemplaza la capa de salida de VGG16 para clasificar las imágenes en las 10 categorías del dataset CIFAR10. VGG16 está diseñado para 1000 clases, por lo que deberás ajustar la capa completamente conectada final (classifier).
8.	Define la función de pérdida como ```CrossEntropyLoss``` y elige un optimizador adecuado, como ```SGD``` o ```Adam```.
9.	Configura los hiperparámetros del entrenamiento, como la tasa de aprendizaje, número de épocas y tamaño del batch.
10.	Entrena el modelo VGG16 utilizando el conjunto de datos CIFAR10. Asegúrate de guardar el progreso y ajustar los hiperparámetros según sea necesario.
11.	Monitorea la precisión y la pérdida en cada época para evaluar el progreso del entrenamiento.
12.	Evalúa el rendimiento del modelo utilizando el conjunto de prueba. Calcula métricas como la precisión global, matriz de confusión, recall y F1-score.
13.	Visualiza los resultados del entrenamiento y la evaluación con gráficos que muestren la evolución de la pérdida y la precisión.
14.	Realiza un reporte donde describas paso a paso la implementación de VGG16, las modificaciones en la arquitectura, los hiperparámetros seleccionados, y los resultados obtenidos.
15.	Comparte tu reporte con el resto de la clase


---

## ❓ **Momento de introspección**

Antes de concluir esta actividad, es importante que tomes un momento para reflexionar y cuestionarte cómo puedes llevar a la práctica los conceptos y habilidades que has adquirido al implementar VGG16. Este ejercicio te permitirá no solo consolidar tu aprendizaje, sino también visualizar su aplicación en contextos del mundo real.

**1.	¿Cómo puedo aplicar lo que aprendí sobre redes neuronales convolucionales (CNN) en otros proyectos o problemas que involucren clasificación de imágenes?**
a.	Piensa en otras áreas, además de CIFAR10, donde las CNN pueden ser útiles, como la medicina, la agricultura, o el análisis de video. ¿Cómo podrías adaptar o mejorar un modelo como VGG16 para esos escenarios?

**2.	¿De qué manera los conocimientos sobre el ajuste de hiper parámetros, como la tasa de aprendizaje o el optimizador, me ayudan a mejorar modelos en otros contextos?**
a.	Considera proyectos pasados o futuros donde el ajuste de estos parámetros pueda mejorar el rendimiento de los modelos. ¿Qué técnicas podrías emplear para optimizar modelos en distintos conjuntos de datos?

**3.	¿Cómo puedo transferir el aprendizaje adquirido en esta actividad a otros dominios del machine learning o deep learning que me interesen?**
a.	Si tu interés es, por ejemplo, el procesamiento de lenguaje natural (NLP) o el análisis de audio, ¿cómo podrían los principios de ajuste de redes neuronales aplicarse en esos campos?

**4.	¿Qué habilidades prácticas o conceptuales he desarrollado en el uso de PyTorch, y cómo puedo seguir perfeccionándolas?**
a.	Piensa en cómo te has familiarizado con PyTorch durante esta actividad. ¿Cómo podrías usar esta habilidad en otros proyectos? ¿Qué desafíos enfrentaste que te gustaría explorar más a fondo para dominarlos?

**5.	¿Cómo puedo integrar el uso de arquitecturas pre entrenadas, como VGG16, en proyectos futuros para acelerar el desarrollo de soluciones?**
a.	Reflexiona sobre los beneficios de usar modelos preentrenados en lugar de entrenar desde cero. ¿En qué casos futuros consideras que sería ventajoso reutilizar arquitecturas preexistentes?

**6.	¿Qué impacto real puede tener la clasificación de imágenes, utilizando redes como VGG16, en la solución de problemas en diferentes industrias?**
a.	Piensa en sectores como la salud, la seguridad, o la robótica. ¿Cómo pueden estas soluciones basadas en visión por computadora influir de manera significativa en la automatización y mejora de procesos?

**7.	¿Qué aprendizajes de esta actividad me motivan a profundizar más en áreas específicas del aprendizaje automático o redes neuronales?**
a.	Ahora que has implementado una red compleja como VGG16, ¿qué otros modelos o técnicas te gustaría investigar? ¿Qué áreas del aprendizaje profundo captaron más tu interés?






