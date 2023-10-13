# Plan de Pruebas

Dado el contexto y la problemática presentada, es importante establecer un plan de pruebas detallado antes de la implementación real de las pruebas automatizadas. Aquí hay un plan de pruebas propuesto para la automatización de pruebas según la funcionalidad indicada en el Anexo 1:

Pruebas de Autenticación (Auth):

- Verificación del código de estado de la respuesta al solicitar un token de autenticación.
- Verificación de la validez y el formato del token de autenticación generado.
- Verificación del código de estado al intentar acceder a recursos protegidos con y sin autenticación.


Pruebas de Reservas (Booking):

- Creación de una reserva con datos válidos y verificación del código de estado y del contenido de la respuesta.
- Lectura de una reserva existente y verificación de la validez de la respuesta y el código de estado.
- Actualización de una reserva existente y verificación de la actualización exitosa.


Pruebas de Ping:

- Verificación del estado de la API mediante la solicitud de ping.
- Comprobación del tiempo de respuesta de la solicitud de ping.

Pruebas de Happy Paths:

- Ejecución de casos de prueba que representen el flujo ideal de la funcionalidad.
- Verificación de que todas las respuestas estén en el formato esperado y que los códigos de estado sean los adecuados.

Pruebas de UnHappy Paths:

- Ejecución de casos de prueba que representen situaciones de error, como enviar datos incorrectos o incompletos.
- Verificación de que se manejen adecuadamente los errores y se devuelvan códigos de estado y mensajes de error apropiados.

Herramientas:

Postman: Para la creación de la colección de pruebas manuales y la automatización de pruebas.
