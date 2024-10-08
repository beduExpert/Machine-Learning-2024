# **Actividad 03 - Chatbot en Messenger**

## 🎯 **Objetivo**
El objetivo de esta actividad es que desarrolles e integres un chatbot utilizando Dialogflow en la plataforma de Facebook Messenger, aplicando los conceptos fundamentales sobre la creación de interacciones conversacionales automatizadas. A través de esta tarea, aprenderás a definir y gestionar intents (intenciones), configurar respuestas enriquecidas y utilizar contextos para mantener un flujo natural en las conversaciones. Además, comprenderás el proceso de integración entre Dialogflow y Facebook Messenger, permitiendo que tu chatbot interactúe con usuarios en tiempo real. Al finalizar la actividad, deberás demostrar el correcto funcionamiento de tu chatbot, documentando su diseño, las dificultades encontradas y las decisiones que tomaste durante el proceso de desarrollo..

---

## 📑 Instrucciones
Con la ayuda del instructor realiza lo siguiente:  

1. Creación de una página de Facebook para tu proyecto final
    1. Entra a [Facebook](https://www.facebook.com/)
    2. Inicia sesión con tu cuenta
    3. En la parte izquierda, da clic en “Ver más”, como se ve a continuación
       <div align="center">
        <img src="images/1.JPG", width="200">
        </div>
    4. A continuación, da clic en “Páginas” y posteriormente en “Crear nuevo perfil o página”
        <div align="center">
        <img src="images/2.JPG", width="400">
        </div>
    6. Da clic en “Página pública” y da clic en “Siguiente”
        <div align="center">
        <img src="images/3.JPG", width="400">
        </div>
    8. Comienza a crear tu página de Facebook sobre tu proyecto final. Por el momento solo crea tu página, la podrás personalizar en otro momento
2. Conectando tu Chatbot de Dialogflow con Messenger de tu página de Facebook. En este caso utilizaré PizzaBot como ejemplo
    1. De lado izquierdo, da clic en “Integrations”
       <div align="center">
        <img src="images/4.JPG", width="200">
        </div>
    2. Buscar “Messenger from Facebook” y dar clic
    3. Ir a https://developers.facebook.com/
    4. Iniciar sesión con la cuenta que se creo la página de Facebook
        <div align="center">
        <img src="images/5.JPG", width="800">
        </div>
    5. Una vez que hayas iniciado sesión, da clic en Mis apps y clic en “Crear App”
       <div align="center">
        <img src="images/6.JPG", width="800">
        </div>

        <div align="center">
        <img src="images/7.JPG", width="400">
        </div>
    6. Da clic en “Siguiente”, como se ve a continuación
       <div align="center">
        <img src="images/8.JPG", width="600">
        </div>
    7. Posteriormente selecciona “Otro” y en “Siguiente”
        <div align="center">
        <img src="images/9.JPG", width="600">
        </div>
    8. Selecciona “Negocios” como el tipo de tu app
        <div align="center">
        <img src="images/10.JPG", width="600">
        </div>
    9. Coloca un nombre a tu app y coloca tu correo electrónico y da clic en “Crear App”
        <div align="center">
        <img src="images/11.JPG", width="600">
        </div>
    10. Una vez que hayas creado tu App, de la página que apareció, en la parte de la derecha, busca “Messenger” y da clic en “Configurar”
        <div align="center">
        <img src="images/12.JPG", width="600">
        </div>
    11. Ve hacía la parte inferior de la página a la sección “2. Generar tokens de acceso” y da clic en “Conectar”
        <div align="center">
        <img src="images/13.JPG", width="600">
        </div>
    12. Selecciona la página a la cual quieres agregar tu Chatbot. En mi caso, agregaré “Pizza_Bot” a la página “Pizza AI”. Posteriormente da clic en “Continuar”, “Guardar” y “De acuerdo”
        <div align="center">
        <img src="images/14.JPG", width="400">
        </div>
    13. Volvemos a ir a la sección “2. Generar tokens de acceso” pero esta vez daremos clic en “Generar”
        <div align="center">
        <img src="images/15.JPG", width="600">
        </div>
    14. Del cuadro de diálogo que te apareció, da clic en “Acepto” y copia el token. Es muy importante que no compartas con nadie este token de acceso.
        <div align="center">
        <img src="images/16.JPG", width="400">
        </div>
    15. Ahora dirígete a tu chatbot en Dialogflow y pega tu token de acceso en el campo “Page Access Token”. Además, en el campo “Verify Token” escribe la palabra “facebook” como palabra de verificación. Por último, da clic en “Start”
        <div align="center">
        <img src="images/17.JPG", width="600">
        </div>
    16. Ahora dirígete a la página de desarrolladores de Facebook, en la sección “1. Configurar webhooks” y da clic en “Configure”
        <div align="center">
        <img src="images/18.JPG", width="600">
        </div>
    17. En el campo “URL de devolución de llamada” pega la información que se encuentra en tu Chatbot en el campo “Callback URL”. En el campo “Token de verificación” escribe tu token de verificación que creaste, en nuestro caso fue “facebook”. Por último da clic en “Verificar y guardar”
        <div align="center">
        <img src="images/19.JPG", width="600">
        </div>
    18. En la página de Facebook developers, en la sección “2. Generar tokens de acceso”, dar clic en “Agregar suscripciones” y agregar las siguientes:
        <div align="center">
        <img src="images/20.JPG", width="600">
        </div>
    19. Por último, clic en “Confirm”
  
3. Probando tu Chatbot en Messenger
    1. Ahora abre Messenger con tu cuenta de facebook
    2. En el buscador, busca el nombre de tu página que está relacionada con tu proyecto final. En mi caso es “Pizza AI”
       <div align="center">
        <img src="images/21.JPG", width="400">
        </div>
    4. Selecciona tu página y comienza a probar tu Chatbot
       <div align="center">
        <img src="images/22.JPG", width="400">
        </div>

4. Presenta tu Chatbot del proyecto final funcionando en Messenger a la clase





---

## ❓ **Momento de introspección**

Al finalizar esta actividad, te invito a tomar un momento de introspección y reflexión sobre lo que has aprendido y cómo ha sido tu experiencia al desarrollar e integrar el chatbot en Messenger. Para guiar esta reflexión, considera las siguientes preguntas:

1.	Proceso de creación: ¿Qué te sorprendió más durante la creación de tu chatbot? ¿Hubo algún concepto o parte del desarrollo que te resultara especialmente desafiante? ¿Cómo lo resolviste?

2.	Interacción con usuarios: ¿Cómo crees que la interacción con usuarios reales en Messenger cambió la forma en que diseñaste las respuestas de tu chatbot? ¿Sentiste que tu chatbot pudo ofrecer respuestas naturales y útiles?

3.	Uso de la tecnología: ¿Cómo te sentiste utilizando herramientas como Dialogflow? ¿Crees que podrías aplicarlas en otros contextos o proyectos? ¿Qué potencial le ves a esta tecnología en el futuro?

4.	Impacto y aprendizaje: ¿Cómo crees que esta experiencia ha influido en tu capacidad para desarrollar soluciones basadas en inteligencia artificial? ¿Cómo te ha ayudado a comprender mejor el diseño de experiencias conversacionales?

5.	Desafíos personales: ¿Qué habilidades personales sentiste que fueron más desafiadas en esta actividad? ¿Fue la creatividad, el pensamiento lógico, la resolución de problemas o alguna otra?

Al responder estas preguntas, piensa en cómo lo aprendido puede ayudarte en futuros proyectos y en tu crecimiento como profesional.








