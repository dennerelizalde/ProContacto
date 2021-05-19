# **EVALUACIÓN PRÁCTICA**

## **EJERCICIO 2**

Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:

1. **¿Qué es un servidor HTTP?**
   Es aquel que aloja archivos web y permite que los clientes puedan acceder a ellos en cualquier momento y a través de un dominio.

2. **¿Qué son los verbos HTTP? Mencionar los más conocidos.**
   Permiten aplicar ciertas acciones a cualquier elemento web, como puede ser el envío o la recepción de información. Algunos de ellos son GET (para consultar un recurso como un sitio web), POST (permite guardar datos como los de un formulario) y PUT (actualiza recursos como la información de un usuario).

3. **¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**
   Un request es cualquier petición que pueda realizar un cliente al servidor para acceder a un recurso, como una página web; mientras que un response es la respuesta que el servidor regresa al cliente, ya sea positiva (mostrar el recurso solicitado) o negativa (indicar un error).
   Los headers son utilizados para anexar información adicional dentro de un request o un response, como el verbo utilizado, el path (URL del recurso solicitado) y el protocolo empleado.

4. **¿Qué es un queryString? (En el contexto de una url).**
   Son los datos que se envían en una URL al momento de realizar un request.

5. **¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?**
   Señalan el estado de un response, ya sea que se realizó correctamente o presentó algún error.
   Las pautas se dividen en respuestas informativas (de 100 a 199, la solicitud está en proceso); satisfactorias (de 200 a 299, la solicitud se realizó correctamente); redirecciones (de 300 a 399, se necesitan acciones adicionales para completar la solicitud); errores del cliente (de 400 a 499, la solicitud es rechazada por una falla cometida por el cliente) y errores del servidor (de 500 a 599, la solicitud es aceptada pero no completada por un problema en el servidor).

6. **¿Cómo se envía data en un Get y cómo en un POST?**
   Con el verbo GET, los datos se envían a través de la URL; mientras que con el verbo POST los datos se encuentran en el header del request, por lo que son prácticamente invisibles para el usuario.

7. **¿Qué verbo http utiliza el navegador cuando accedemos a una página?**
   Como mencioné en la pregunta 2, el verbo GET permite acceder a una página web o cualquier otro recurso.

8. **Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**
   JSON define una sintaxis concreta para que la transferencia de datos entre el cliente y el servidor sea eficaz. Su estructura está basada en los objetos de JavaScript (de aquí proviene su nombre), compuestos por llaves y valores. A continuación, se muestra un ejemplo:
   
   <img src="images/ejemploJSON.jpg" width="300">
   
   XML es un lenguaje basado en etiquetas para ordenar información de manera jerárquica y optimizar su uso. El ejemplo utilizado anteriormente, pero en formato XML, sería el siguiente:
   
   <img src="images/ejemploXML.jpg" width="350">
   
9. **Explicar brevemente el estándar SOAP.**
Es un protocolo con determinadas reglas para establecer una comunicación satisfactoria entre dos servicios web con lenguajes y plataformas diferentes.

10. **Explicar brevemente el estándar REST Full.**
REST está formado por un conjunto de principios flexibles para el intercambio de información en servicios web y aplicaciones móviles ligeras. A los servicios que utilizan esta arquitectura se les conoce como servicios RESTful

11. **¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**
Los headers en un request agregan más detalles sobre la petición o ayudan a darle un mejor contexto. Algunos de ellos son host (dirección a la que va dirigida el request); user-agent (incluye el nombre y versión del navegador y del sistema operativo del usuario) y accept-language (lenguaje predeterminado del usuario).
El content-type, como su nombre lo indica, especifica al navegador el tipo de archivo que se va a consultar para que pueda interpretarlo de forma correcta.

### _**Fuentes consultadas**_
* Digital Guide IONOS. (2019). ¿Qué es un servidor web y qué soluciones de software existen?. 18 de mayo de 2021, de 1&1 IONOS. Sitio web: https://www.ionos.mx/digitalguide/servidores/know-how/servidor-web-definicion-historia-y-programas/
* MDN Web Docs. (2021). Que es un servidor WEB?. 18 de mayo de 2021, de Mozilla Corporation. Sitio web: https://developer.mozilla.org/es/docs/Learn/Common_questions/What_is_a_web_server
* MDN Web Docs. (2021). Métodos de petición HTTP. 18 de mayo de 2021, de Mozilla Corporation Sitio web: https://developer.mozilla.org/es/docs/Web/HTTP/Methods
* Victor Robles WEB. (2019). Métodos HTTP ¡EXPLICADOS! Diferencia entre GET, POST, PUT y DELETE. Crear un BACKEND RESTful. 18 de mayo de 2021, de YouTube. Sitio web: https://www.youtube.com/watch?v=dXF3cc8mkHM
* render2web. (2021). Petición y Respuesta Http - Request - Response PHP Video. 18 de mayo de 2021, de YouTube. Sitio web: https://www.youtube.com/watch?v=vs0ekUJ1rd8
* MDN Web Docs. (2021). HTTP headers. 18 de mayo de 2021, de Mozilla Corporation. Sitio web: https://developer.mozilla.org/es/docs/Web/HTTP/Headers
* GitBook. (s/f). Query String. 18 de mayo de 2021, de GitBook. Sitio web: https://analizador-lex-pjv.herokuapp.com/cookies/chapter3.html
* Lázaro, D. (2018). Códigos de estado HTTP. 18 de mayo de 2021, de Diego.com.es. Sitio web: https://diego.com.es/codigos-de-estado-http
* Penland, J. (2021). Una guía completa y una lista de códigos de estado HTTP. 18 de mayo de 2021, de Kinsta. Sitio web: https://kinsta.com/es/blog/codigos-de-estado-de-http/
* Digital Guide IONOS. (2020). HTTP Request: los métodos de petición que debes conocer. 18 de mayo de 2021, de 1&1 IONOS. Sitio web: https://www.ionos.es/digitalguide/hosting/cuestiones-tecnicas/http-request/#:~:text=HTTP%20Request%3A%20los%20métodos%20de,ha%20de%20responder%20el%20servidor.
* MDN Web Docs. (2021). Trabajando con JSON. 18 de mayo de 2021, de Mozilla Corporation. Sitio web: https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/JSON
* W3Schools. (s/f). JSON - Introduction. 18 de mayo de 2021, de W3Schools. Sitio web: https://www.w3schools.com/js/js_json_intro.asp
* González, R. (2021). ¿Qué es XML en programación? Te explicamos punto por punto de qué se trata esta herramienta. 18 de mayo de 2021, de Crehana. Sitio web: https://www.crehana.com/mx/blog/tech/que-es-xml/
* Red Hat. (s/f). Diferencias entre REST y SOAP. 18 de mayo de 2021, de Red Hat. Sitio web: https://www.redhat.com/es/topics/integration/whats-the-difference-between-soap-rest
* Chakray. (s/f). ¿Qué diferencias hay entre REST y SOAP?. 18 de mayo de 2021, de Chakray. Sitio web: https://www.chakray.com/es/que-diferencias-hay-entre-rest-y-soap/
* Guzel, B. (2021). Cabeceras HTTP para Dummies. 18 de mayo de 2021, de Envato. Sitio web: https://code.tutsplus.com/es/tutorials/http-headers-for-dummies--net-8039

## **EJERCICIO 3**
Recomendamos previamente entender los conceptos de la sintaxis “json” antes de arrancar con los ejercicios.
Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:
1. **Realizar un request GET a la URL: https://reclutamiento-14cf7.firebaseio.com/personas.json**
<img src="images/requestGET1.jpg">

2. **Realizar un request POST a la URL anterior, y con body: {"nombre":"Tu nombre", "apellido":"Tu apellido", "dni":11223322} Tip: (Marcar la opción “raw” como body)**
<img src="images/requestPOST.jpg">

3. **Realizar nuevamente un request GET a la URL: https://reclutamiento-14cf7.firebaseio.com/personas.json ¿Qué diferencias se observan?** Se agregaron mis datos al archivo JSON.
<img src="images/requestGET2.jpg">
