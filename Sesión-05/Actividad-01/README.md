# **Actividad 01 - Clasificación de Imágenes con CNN**

## 🎯 **Objetivo**
El objetivo de esta actividad es que implementes y comprendas el funcionamiento de VGG16, una arquitectura clásica de redes neuronales convolucionales, utilizando la biblioteca PyTorch para la clasificación de imágenes. A través de esta actividad, desarrollarás habilidades prácticas en el uso de PyTorch para la creación y entrenamiento de modelos de deep learning. Utilizando el conjunto de datos CIFAR10, entrenarás a VGG16 para clasificar imágenes en 10 categorías diferentes, profundizando así en el proceso de ajuste y optimización de modelos de redes neuronales.

---

## 📑 Instrucciones
1.	Abre el cuaderno proporcionado, el cual lo puedes encontrar en [Cuaderno]()
2.	Carga del Dataset CIFAR10 desde [Link](https://www.kaggle.com/datasets/swaroopkml/cifar10-pngs-in-folders)
3.	Divide el dataset en conjuntos de entrenamiento y prueba.
4.	Asegúrate de normalizar las imágenes utilizando ``` torchvision.transforms ```  para que los valores de píxeles estén en un rango adecuado.
5.	Importa la arquitectura VGG16 desde ```torchvision.models```.
6.	Carga el modelo preentrenado y reemplaza la capa de salida de VGG16 para clasificar las imágenes en las 10 categorías del dataset CIFAR10. VGG16 está diseñado para 1000 clases, por lo que deberás ajustar la capa completamente conectada final (classifier).
7.	Define la función de pérdida como CrossEntropyLoss y elige un optimizador adecuado, como SGD o Adam.
8.	Configura los hiperparámetros del entrenamiento, como la tasa de aprendizaje, número de épocas y tamaño del batch.
9.	Entrena el modelo VGG16 utilizando el conjunto de datos CIFAR10. Asegúrate de guardar el progreso y ajustar los hiperparámetros según sea necesario.
10.	Monitorea la precisión y la pérdida en cada época para evaluar el progreso del entrenamiento.
11.	Evalúa el rendimiento del modelo utilizando el conjunto de prueba. Calcula métricas como la precisión global, matriz de confusión, recall y F1-score.
12.	Visualiza los resultados del entrenamiento y la evaluación con gráficos que muestren la evolución de la pérdida y la precisión.
13.	Realiza un reporte donde describas paso a paso la implementación de VGG16, las modificaciones en la arquitectura, los hiperparámetros seleccionados, y los resultados obtenidos.
14.	Comparte tu reporte con el resto de la clase


---

## ❓ **Momento de introspección**

Al finalizar esta actividad, tómate unos minutos para reflexionar sobre lo que has aprendido y cómo puedes aplicar estos conocimientos en otros contextos. Aquí tienes algunas preguntas que pueden ayudarte en este proceso de introspección:

**¿Cómo se relaciona lo aprendido hoy con situaciones de la vida real?**
Piensa en otros productos o servicios cuyos precios podrían predecirse utilizando redes neuronales. ¿Qué otras variables deberías tener en cuenta en esos casos?

**¿De qué manera este conocimiento puede mejorar mi capacidad de resolver problemas?**
Reflexiona sobre cómo la capacidad de predecir valores o comportamientos a través de algoritmos avanzados podría aplicarse a otros problemas complejos en tu área de estudio o trabajo.

**¿Qué aspectos del desarrollo del modelo me parecieron más desafiantes y por qué?**
¿En qué áreas necesitas más práctica? ¿Qué estrategias puedes aplicar para mejorar tu comprensión o habilidad en esos aspectos?

**¿Cómo puedo aplicar lo aprendido a otros proyectos o desafíos personales?**
Imagina un proyecto personal o académico donde podrías usar redes neuronales. ¿Cómo estructurarías el problema y qué datos necesitarías?

**¿Cómo cambiaría mi enfoque si tuviera que enseñar esto a alguien más?**
 Si tuvieras que explicar este concepto a un compañero, ¿cómo lo harías? ¿Qué ejemplos prácticos o analogías usarías para facilitar su comprensión?

**¿Qué impacto tiene el uso de redes neuronales en la sociedad y en mi campo de estudio?**
Piensa en el impacto que las redes neuronales y la inteligencia artificial tienen en diferentes industrias. ¿Cómo puedes contribuir a un uso responsable y ético de estas tecnologías?





