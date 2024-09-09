# **Actividad 02 - CClasificación de imágenes sobre un dataset customizado**

## 🎯 **Objetivo**
El objetivo de la Actividad 02 es que implementes una red neuronal convolucional (CNN) en un dataset customizado, con el fin de desarrollar y adaptar modelos de deep learning a problemas específicos. Utilizando arquitecturas como VGG16 o alternativas que elijas, podrás personalizar la red para ajustarse a las características de tu dataset, experimentar con diferentes configuraciones y técnicas de entrenamiento, y evaluar el desempeño del modelo en tareas de clasificación. A través de esta actividad, adquirirás experiencia práctica en la aplicación de redes neuronales convolucionales a datos personalizados, mejorando tu habilidad para enfrentar desafíos en escenarios del mundo real.

---

## 📑 Instrucciones
De manera independiente, realiza lo siguiente:

1.	Asegúrate de tener PyTorch y las bibliotecas necesarias instaladas en tu entorno de desarrollo. Si aún no lo has hecho, consulta la página oficial de PyTorch para la instalación.
2.	Recolecta un dataset customizado en [Kaggle](www.kaggle.com) que desees utilizar. Asegúrate de que esté bien etiquetado y dividido en conjuntos de entrenamiento y prueba.
3.	Utiliza ```torchvision.datasets.ImageFolder``` o implementa un ```Datase```t personalizado para cargar tus datos en PyTorch.
4.	Aplica transformaciones adecuadas a las imágenes, como redimensionamiento, normalización y aumentos de datos, utilizando ```torchvision.transforms```.
5.	Elige una arquitectura de red neuronal convolucional (CNN) para implementar, como VGG16, o considera otras arquitecturas como GoogLeNet o AlexNet si prefieres.
6.	Importa el modelo seleccionado desde ```torchvision.models``` o implementa la arquitectura desde cero según tus necesidades.
7.	Si estás utilizando una red preentrenada, ajusta la última capa para que coincida con el número de clases de tu dataset customizado.
8.	Define la función de pérdida y el optimizador adecuados. La función de pérdida comúnmente utilizada es ```CrossEntropyLoss```, y los optimizadores pueden ser ```SG```D, ```Adam```, entre otros.
9.	Configura los hiper parámetros de entrenamiento como la tasa de aprendizaje, número de épocas y tamaño del batch.
10.	Entrena la red CNN con tu dataset customizado. Monitorea la precisión y la pérdida en cada época para ajustar los hiperparámetros si es necesario.
11.	Evalúa el modelo entrenado en el conjunto de prueba. Calcula métricas de rendimiento como la precisión, la matriz de confusión, recall y F1-score.
12.	Redacta un informe detallado sobre el proceso que seguiste para implementar y entrenar la red CNN. Incluye la arquitectura utilizada, modificaciones realizadas, hiper parámetros ajustados y resultados obtenidos.
13.	Incluye gráficos que muestren la evolución de la pérdida y precisión durante el entrenamiento, así como ejemplos de las predicciones del modelo en el conjunto de prueba.
14.	Comparte con el resto de la clase tu informe



---

## ❓ **Momento de introspección**

Ahora que has completado la implementación de una red neuronal convolucional (CNN) en tu dataset customizado, es un buen momento para reflexionar sobre el proceso y considerar cómo puedes aplicar lo aprendido en futuras experiencias. Tómate unos minutos para pensar en las siguientes preguntas:

**1.	¿Qué desafíos encontraste al trabajar con tu dataset customizado y cómo los superaste?**
a.	Reflexiona sobre las dificultades que encontraste durante la preparación de los datos, la implementación del modelo o el ajuste de hiperparámetros. ¿Qué estrategias utilizaste para resolver estos problemas?

**2.	¿Cómo influyeron las características específicas de tu dataset en el diseño y entrenamiento de la CNN?**
a.	Considera cómo las particularidades de tu dataset, como el tamaño, la variedad y la calidad de las imágenes, afectaron el rendimiento de tu modelo. ¿Qué ajustes realizaste para adaptar el modelo a estas características?

**3.	¿Cómo puedes aplicar los conocimientos adquiridos en esta actividad a otros problemas o proyectos en el futuro?**
a.	Reflexiona sobre cómo la experiencia de trabajar con CNNs y datasets personalizados puede ayudarte en futuros proyectos. ¿Qué habilidades o enfoques aprendidos puedes utilizar en otros contextos o áreas del machine learning?

**4.	¿Qué aspectos del proceso de entrenamiento y evaluación te gustaría explorar más a fondo?**
a.	Considera las áreas del entrenamiento y evaluación que te resultaron más interesantes o desafiantes. ¿Hay técnicas o metodologías adicionales que te gustaría investigar para mejorar tus modelos?

**5.	¿De qué manera puedes mejorar la eficiencia y la efectividad de tus modelos en proyectos futuros?**
a.	Piensa en cómo podrías optimizar el rendimiento de tus modelos, desde la preparación de datos hasta la selección de hiper parámetros y técnicas de regularización. ¿Qué cambios podrías implementar para lograr mejores resultados en proyectos similares?
red compleja como VGG16, ¿qué otros modelos o técnicas te gustaría investigar? ¿Qué áreas del aprendizaje profundo captaron más tu interés?






