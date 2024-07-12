1. ¿Qué es el filesystem (fs) en Node.js y para qué se utiliza?

El módulo fs en Node.js proporciona una API para interactuar con el sistema de archivos. Permite leer, escribir, actualizar y eliminar archivos y directorios. Es útil para tareas como la gestión de archivos de configuración, almacenamiento de datos o manejo de archivos subidos por usuarios.
2. ¿Qué es un middleware en Express y cuál es su propósito?

Un middleware en Express es una función que tiene acceso al objeto de solicitud (req), al objeto de respuesta (res) y a la siguiente función de middleware en la pila. Su propósito es ejecutar código, realizar transformaciones, gestionar errores, o finalizar la solicitud y respuesta. Se utiliza para tareas como la autenticación, manejo de errores y la manipulación de datos de entrada.
3. ¿Qué es un endpoint en una API RESTful y cuál es su función?

Un endpoint es una URL que representa un recurso en una API RESTful. Su función es recibir solicitudes de los clientes y devolver respuestas, permitiendo la interacción con los datos de la aplicación. Cada endpoint está asociado con una acción específica sobre un recurso, como obtener, crear, actualizar o eliminar.
4. ¿Qué son los verbos HTTP y cuáles son los más comunes?

Los verbos HTTP son métodos que indican la acción a realizar en un recurso. Los más comunes son:

    GET: Recuperar datos.
    POST: Crear nuevos recursos.
    PUT: Actualizar recursos existentes.
    DELETE: Eliminar recursos.

5. ¿Qué es JSON y por qué es utilizado en las API RESTful?

JSON (JavaScript Object Notation) es un formato ligero de intercambio de datos que es fácil de leer y escribbir, y fácil de parsear y generar para las máquinas. Se utiliza en APIs RESTful debido a su simplicidad y compatibilidad con la mayoría de lenguajes de programación.
6. En lo que respecta al envío de datos a lo largo de los verbos HTTP:

    ¿Qué es el body de una petición?
    El body de una petición es el contenido enviado por el cliente al servidor, como datos de formularios o archivos.

    ¿Qué es el body de una respuesta?
    El body de una respuesta es el contenido enviado por el servidor al cliente en respuesta a una solicitud, a menudo incluye datos en formato JSON.

    ¿Qué es el query de una petición?
    El query de una petición son los parámetros que se envían en la URL después del signo de interrogación (?), usados para filtrar o buscar recursos.

    ¿Qué es el params de una petición?
    El params de una petición son segmentos de la URL que son variables, usados para identificar recursos específicos (por ejemplo, /usuarios/:id).

7. En lo que respecta al verbo POST:

    ¿Qué es un verbo POST y cuál es su propósito?
    Un verbo POST se utiliza para crear nuevos recursos en el servidor.

    ¿Cuándo se utiliza un verbo POST?
    Se utiliza cuando se envían datos para crear un nuevo recurso en el servidor.

    ¿En qué se diferencia un verbo POST de los otros verbos HTTP como GET, PUT y DELETE?
    A diferencia de GET (que no modifica recursos), PUT (que actualiza) y DELETE (que elimina), POST se centra en la creación.

    ¿Cómo se envían datos en un verbo POST?
    Los datos se envían en el body de la petición.

8. En lo que respecta al verbo GET:

    ¿Qué es un verbo GET y cuál es su propósito?
    Un verbo GET se utiliza para recuperar datos del servidor.

    ¿Cuándo se utiliza un verbo GET?
    Se utiliza para solicitar datos sin modificar el estado del recurso.

    ¿En qué se diferencia un verbo GET de los otros verbos HTTP como POST, PUT y DELETE?
    A diferencia de POST (que crea), PUT (que actualiza) y DELETE (que elimina), GET es solo para lectura.

9. En lo que respecta al verbo PUT:

    ¿Qué es un verbo PUT y cuál es su propósito?
    Un verbo PUT se utiliza para actualizar recursos existentes.

    ¿Cuándo se utiliza un verbo PUT?
    Se utiliza cuando se envían datos para reemplazar un recurso existente en el servidor.

    ¿En qué se diferencia un verbo PUT de los otros verbos HTTP como POST, GET y DELETE?
    A diferencia de POST (que crea), GET (que lee) y DELETE (que elimina), PUT se utiliza específicamente para actualizaciones.

10. En lo que respecta al verbo DELETE:

    ¿Qué es un verbo DELETE y cuál es su propósito?
    Un verbo DELETE se utiliza para eliminar recursos.

    ¿Cuándo se utiliza un verbo DELETE?
    Se utiliza cuando se desea eliminar un recurso del servidor.

    ¿En qué se diferencia un verbo DELETE de los otros verbos HTTP como POST, GET y PUT?
    A diferencia de POST (que crea), GET (que lee) y PUT (que actualiza), DELETE se centra en la eliminación.

11. ¿Qué es un status code y cuáles son los más comunes?

Un status code es un código de respuesta HTTP que indica el resultado de una solicitud. Los más comunes son:

    200: OK
    201: Created
    204: No Content
    400: Bad Request
    401: Unauthorized
    404: Not Found
    500: Internal Server Error

12. ¿Cuáles son los status codes más comunes para el verbo POST?

    201: Created (al crear un recurso).
    400: Bad Request (error en los datos enviados).
    500: Internal Server Error (error en el servidor).

13. ¿Cuáles son los status codes más comunes para el verbo GET?

    200: OK (solicitud exitosa).
    404: Not Found (recurso no encontrado).

14. ¿Cuáles son los status codes más comunes para el verbo PUT?

    200: OK (actualización exitosa).
    204: No Content (actualización exitosa sin contenido en la respuesta).
    400: Bad Request (error en los datos enviados).

15. ¿Cuáles son los status codes más comunes para el verbo DELETE?

    204: No Content (eliminación exitosa).
    404: Not Found (recurso no encontrado).
