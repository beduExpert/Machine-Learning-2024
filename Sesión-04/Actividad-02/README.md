# **Actividad 02 - Clasificación de Objetos Estelares**

## 🎯 **Objetivo**
El objetivo de esta actividad es que utilices redes neuronales para llevar a cabo la clasificación de objetos estelares, como galaxias, estrellas y quásares, de manera independiente. A través de esta tarea, aplicarás los conocimientos adquiridos sobre redes neuronales en un contexto de astronomía, desarrollando un modelo que permita identificar y categorizar estos objetos a partir de datos astronómicos. Al finalizar, habrás adquirido una comprensión más profunda sobre el proceso de clasificación mediante aprendizaje automático y cómo utilizar las redes neuronales para resolver problemas complejos en distintos campos de estudio.

---

## 📑 Instrucciones
**1.	Preparación del Entorno**
* Asegúrate de tener instalado Python y las bibliotecas necesarias como TensorFlow o PyTorch, Pandas, y Scikit-learn.
* Descarga el conjunto de datos astronómicos de la siguiente [liga](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17), que incluye características de diferentes objetos estelares como galaxias, estrellas y quásares.

**3.	Análisis Exploratorio de Datos**
*	Carga el conjunto de datos en Python utilizando Pandas.
*	Realiza un análisis exploratorio de los datos para entender las características y etiquetas de los objetos estelares. Esto te ayudará a identificar qué atributos son más relevantes para la clasificación.
*	Asegúrate de visualizar los datos a través de gráficos que te permitan interpretar mejor las relaciones entre las variables.

**4.	Preprocesamiento de los Datos**
*	Limpia los datos eliminando valores nulos o inconsistentes.
*	Normaliza los datos si es necesario, para asegurar que las características estén en un rango adecuado para el entrenamiento del modelo.
*	Divide el conjunto de datos en un conjunto de entrenamiento y otro de prueba, asegurando una correcta distribución de las clases de objetos estelares.

**5.	Construcción del Modelo**
*	Utilizando TensorFlow o PyTorch, construye una red neuronal con una capa de entrada que reciba las características de los objetos estelares, una o más capas ocultas, y una capa de salida con tantas neuronas como clases (galaxias, estrellas y quásares).
*	Define la función de activación, el optimizador, y la función de pérdida adecuada para un problema de clasificación (por ejemplo, la entropía cruzada).

**6.	Entrenamiento del Modelo**
*	Entrena la red neuronal utilizando los datos de entrenamiento.
*	Ajusta los hiperparámetros como el número de épocas, tamaño del lote (batch size) y la tasa de aprendizaje.
*	Monitorea las métricas de precisión y pérdida durante el entrenamiento para asegurarte de que el modelo está mejorando sin sobreajustarse.

**7.	Evaluación del Modelo**
*	Evalúa el modelo utilizando los datos de prueba.
*	Analiza el desempeño del modelo en la clasificación de objetos estelares, comparando las predicciones con las etiquetas reales.
*	Calcula métricas de evaluación como la precisión, la sensibilidad y el F1 score para medir el rendimiento del modelo.

**8.	Optimización del Modelo**
*	Si es necesario, ajusta el número de capas, neuronas o hiperparámetros del modelo para mejorar su precisión.
*	Reentrena el modelo y vuelve a evaluar sus resultados.

**9.	Informe de Resultados**
*	Documenta el proceso seguido, los resultados obtenidos y cualquier ajuste realizado al modelo.
*	Incluye gráficos y análisis de las métricas de evaluación que muestren cómo tu modelo clasifica los diferentes objetos estelares.
*	Prepara un informe final en formato PDF.

**10.	Entrega**
*	Sube el código del modelo y el informe final a la plataforma indicada por el instructor antes de la fecha límite.


---

## ❓ **Momento de introspección**

Al finalizar esta actividad, dedica unos minutos a reflexionar sobre tu proceso de aprendizaje y cómo lo que has realizado puede impactar tu formación y aplicación futura. Aquí algunas preguntas para guiar tu introspección:

**1.	¿Cómo esta actividad me ha ayudado a comprender mejor las redes neuronales y su aplicación?** ¿Qué fue lo más revelador o novedoso al aplicar redes neuronales para clasificar objetos estelares?

**2.	¿Qué dificultades encontré durante el desarrollo del modelo y cómo las superé?** Reflexiona sobre los pasos del preprocesamiento de datos o la construcción del modelo. ¿Hubo algo que te costó más trabajo entender o implementar? ¿Cómo lo resolviste?

**3.	¿En qué otros campos o problemas podría aplicar lo aprendido hoy?** Piensa en otros conjuntos de datos que podrías clasificar utilizando redes neuronales. ¿Qué similitudes o diferencias habría con el problema de clasificación de objetos estelares?

**4.	¿Cómo puedo mejorar mi enfoque en futuros proyectos similares?** Si tuvieras que repetir esta actividad o aplicar estos conocimientos a otro problema, ¿qué harías diferente? ¿Cómo optimizarías tu tiempo o recursos?

**5.	¿Qué impacto tienen estas técnicas de clasificación en el campo de la astronomía y otros sectores científicos?** Reflexiona sobre cómo el uso de redes neuronales está transformando la ciencia. ¿Cómo podrías contribuir a esa evolución en tu futuro profesional?

**6.	¿Qué habilidades técnicas y de pensamiento he fortalecido con esta actividad?** ¿Te sientes más cómodo/a trabajando con redes neuronales y procesando datos? ¿De qué manera esta experiencia ha influido en tu forma de abordar problemas complejos?






