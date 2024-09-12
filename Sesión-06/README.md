🏠 [**Inicio**](../README.md) ➡️ / 📖 `Sesión 01`

<div align="center">
    <img src="../BEDU.JPG" alt="Sesion_01">
</div>

## 🎯 Objetivos

⚒️ El objetivo de esta sesión es que adquieras una comprensión profunda sobre el funcionamiento de las Redes Neuronales Recurrentes (RNNs) y sus variantes, enfocándote en su capacidad para procesar secuencias de datos y capturar dependencias temporales. A través del estudio de aplicaciones como el Procesamiento de Lenguaje Natural (NLP) y el Análisis de Sentimientos, desarrollarás las habilidades necesarias para implementar RNNs en problemas reales. Además, conocerás las limitaciones de las RNN tradicionales y cómo arquitecturas avanzadas como LSTM y GRU permiten resolver dichos problemas, aplicándolas en tareas de predicción de secuencias y procesamiento de lenguaje.

---

📘 Material del prework:
En el prework podrás encontrar la parte teórica que utilizaremos para realizar los ejercicios de esta sesión. 
🔥¡Vamos a comenzar!🔥

---

## 📂 Temas de la sesión...


### 📖 Procesamiento de lenguaje natural

Los lenguajes naturales (también conocidos como lenguajes ordinarios) son aquellos que son hablados o escritos por las personas para comunicaciones de propósito general. El lenguaje es un sistema, un conjunto de reglas o símbolos, que, combinados, conllevan información. El Procesamiento de Lenguaje Natural (NLP, por sus siglas en inglés) es un campo de la inteligencia artificial que se centra en la interacción entre los computadores y el lenguaje humano. Su objetivo es hacer que las máquinas sean capaces de entender, interpretar y generar lenguaje de manera similar a como lo hacen los humanos.

---

### 📖 ¿Qué es una RNN?

Las Redes Neuronales Recurrentes (RNN) son un tipo de red neuronal adaptada para trabajar con datos en series de tiempo. Este tipo de redes se entrenan para convertir una secuencia de datos en otra secuencia de datos, por ejemplo, la traducción de textos. Las RNNs se distinguen por su capacidad para manejar secuencias de datos mediante la incorporación de ciclos en sus conexiones. Estos ciclos permiten que la información fluya de una etapa temporal a la siguiente, lo que proporciona una "memoria" del contexto anterior.

---

### 📖 Long short-term memory (LSTM)

Las Long Short-Term Memory (LSTM) son una arquitectura avanzada dentro de las RNNs, específicamente diseñada para abordar las limitaciones de las RNN tradicionales. Las RNN convencionales presentan dificultades cuando intentan aprender de secuencias de datos largas debido a problemas como el desvanecimiento y la explosión del gradiente. Estos problemas surgen cuando las redes intentan retropropagar los gradientes a lo largo de muchas capas o pasos temporales, lo que provoca que los gradientes se vuelvan extremadamente pequeños (desvanecimiento) o crezcan exponencialmente (explosión). Como resultado, las RNN tienen dificultades para capturar dependencias a largo plazo, lo que limita su capacidad para modelar secuencias complejas y prolongadas.

---

### 📖 Gated recurrent unit (GRU)

Las Gated Recurrent Units (GRU), como las LSTM, son una evolución de las redes RNN convencionales, diseñadas para mejorar su capacidad en la captura de dependencias a largo plazo dentro de secuencias de datos. Las LSTM como las GRU, fueron diseñadas para resolver los mismos problemas de las RNN tradicionales, sin embargo, las LSTM  lo hacen con una estructura más compleja que incluye varias puertas (entrada, olvido y salida) y una célula de memoria separada que controla el flujo de información. Las GRU, por otro lado, simplifican esta arquitectura. Aunque también utilizan un mecanismo de puertas, reducen el número de estas a dos: la puerta de actualización y la puerta de reinicio, eliminando la célula de memoria separada. 


---

### ✏️ Actividades

#### 📕 **[Actividad 01: Clasificación de Sentimientos en Tweets](/Sesión-06/Actividad-01/README.md)**
#### 📕 **[Actividad 02: Clasificación de Sentimientos sobre un Dataset Customizado](/Sesión-06/Actividad-02/README.md)**


---

⬅️ [**Anterior**](../Sesión-05/README.md) | [**Siguiente**](../Sesión-07/README.md)➡️
