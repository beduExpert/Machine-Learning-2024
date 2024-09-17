# **Actividad 01 -PizzaBot**

## 🎯 **Objetivo**
El objetivo principal de esta actividad es desarrollar un chatbot utilizando Dialogflow que permita a los usuarios realizar pedidos de pizza de manera rápida y eficiente, al mismo tiempo que responde a consultas relacionadas con el menú, precios y promociones. A través de la implementación de procesamiento del lenguaje natural (NLP), reconocimiento de intenciones y entidades, el chatbot será capaz de identificar y comprender las solicitudes de los clientes, generando respuestas personalizadas y dinámicas. De este modo, los estudiantes podrán aplicar habilidades de diseño de chatbots y mejorar la experiencia del cliente, automatizando el proceso de orden en una pizzería virtual.

---

## 📑 Instrucciones
Con la ayuda del instructor, sigue las siguientes instrucciones para crear tu PizzaBot.
1. Entra a [Dialogflow](https://dialogflow.cloud.google.com)
2. Da clic en “Create Agent”
3. Coloca el nombre de “PizzaBot” a tu chatbot
4. Selecciona el idioma con el cual te comunicarás con PizzaBot y da clic en “Create”
5. Da clic en “Create Intent” para crear una intención
6. Nombra tu intent como “hora_apertura” y da clic en “training phrases"
7.	Da clic en “Add training phrases"
8.	Agrega las siguientes preguntas con las cuales el chatbot entrenará
9.	Navega hacia debajo de la ventana y da clic en “Add response” para agregar las respuestas que te gustaría que el chatbot respondiera a las preguntas arriba declaradas.
10.	Da clic en “Save” en la esquina superior izquierda para guardar los cambios
11.	Prueba tu PizzaBot utilizando el panel izquierdo de la página preguntando por los horarios de apertura.
12.	PizzaBot reconocerá el intent y responderá a tu pregunta
13.	Ahora crearemos un intent para ordenar pizzas
14.	Crea un nuevo intent como “ordenar_pizza”
15.	Agrega “training phrases”
16.	Agrega las respuestas
17.	Guarda el intent
18.	Prueba el intentando ordenar una pizza con una pregunta que no usaste como “training phrase”, como, por ejemplo, “me das una pizza?”
19.	Ahora es tiempo de crear una “Entity”. Damos clic en “Entities” y luego en “Create Entity”
20.	Nombra a la “Entity” como tipo_pizza, selecciona “Define synoniyms” y agrega los tipos de pizza y sus sinónimos
21.	Dirígete a la sección de “Intent” y modifica el intent ordenar_pizza agregando nuevas training phrases refiriéndose a los tipos de pizza
22.	De los nuevos training phrases, selecciona los tipos de pizza y anótalas (labelling) como tipo_pizza
24.	Ahora, modifica las respuestas para que incluya el tipo de pizza
25.	Guarda el intent y prueba el bot
26.	Observa cómo el bot entiende la “Entity” de la que estas hablando y la incluye en su respuesta
27.	¿Qué pasa si solo ordenas una pizza sin decirle qué tipo? Inténtalo
28.	Debido a que todas tus respuestas incluyen el entity $tipo_pizza, cuando ordenas una pizza sin especificar el tipo, no hay una respuesta para ello. Para solucionar este problema, regresa a la sección de intents y marca como obligatorio el $tipo_pizza y agrega un prompt para preguntar al usuario el tipo de pizza.
29.	Guarda el intent e intenta de nuevo pedir una pizza sin especificar el tipo.
30.	Completa el chatbot para que sea capaz de realizar lo siguiente:
a.	Saludar
b.	Preguntar qué desea ordenar el usuario
c.	Dar información de tipos de pizza
d.	Dar información de precios
e.	Dar información de tamaños
f.	Realizar un pedido
g.	Despedirse
31.	Comparte frente a la clase el funcionamiento de tu Pizzabot terminado
32.	Recibe retroalimentación de tus compañeros e instructor.



---

## ❓ **Momento de introspección**

Antes de avanzar, tómate un momento para reflexionar sobre lo que has aprendido hasta ahora. Considera cómo el desarrollo de un chatbot puede tener un impacto directo en la automatización de procesos, la mejora de la experiencia del cliente y la eficiencia en los negocios. Pregúntate:

•	¿Cómo podrías aplicar las técnicas de procesamiento del lenguaje natural (NLP) en otros contextos, además de la venta de pizzas? ¿Qué otros sectores o industrias se beneficiarían de un chatbot?

•	Durante la creación del chatbot, ¿qué desafíos encontraste al reconocer las intenciones del usuario? ¿Cómo podrías mejorar el reconocimiento de intenciones para hacer el chatbot más preciso?

•	¿Cómo puedes aprovechar entidades y contextos para crear una experiencia conversacional más fluida y personalizada? ¿En qué otros casos de uso podrías aplicar estos conceptos?

•	¿De qué manera el uso de una herramienta como Dialogflow facilita la creación de chatbots comparado con el desarrollo desde cero? ¿Crees que podrías construir un chatbot más avanzado utilizando esta plataforma?

•	Piensa en un entorno laboral o proyecto personal: ¿Cómo implementarías un chatbot en ese contexto? ¿Qué beneficios aportarías con esta tecnología?


Reflexionar sobre estas preguntas te permitirá pensar en nuevas oportunidades para aplicar lo aprendido, no solo en el proyecto actual, sino en futuros retos profesionales.







