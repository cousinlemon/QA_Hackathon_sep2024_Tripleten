# Hackaton-equipo04

<h2 style="font-size:50px;">Presentación </h2>
Para garantizar la máxima calidad en nuestros desarrollos, optamos por realizar pruebas exhaustivas manuales en las tres plataformas: Platzi, Booker y Bugbank. Trabajamos sin requisitos definidos, lo que significaba que avanzamos basándonos en nuestro instinto, lógica y en lo que consideramos más importante para el usuario final. Este enfoque nos permitió priorizar la experiencia del usuario, evaluando los sistemas en función de los tipos de datos que teníamos a la mano: string, numérico y booleano.

Cubrimos las distintas formas en que las aplicaciones interactúan con la entrada y salida de datos, asegurando un rendimiento óptimo para los usuarios finales. No solo validamos que las aplicaciones respondieran adecuadamente a estos datos, sino que también observamos su comportamiento bajo diversas condiciones y casos límite. Al no tener requisitos específicos, nos enfocamos en lo que consideramos crítico para la funcionalidad y usabilidad, realizando pruebas en los aspectos que consideramos más relevantes para el usuario, garantizando una experiencia fluida y satisfactoria.

<h2 style="font-size:30px;">Proyecto: Platzi  </h2>
Realizamos pruebas sin contar con requisitos definidos, por lo que trabajamos de manera intuitiva, aplicando nuestra lógica y priorizando lo que consideramos más importante para el usuario final. Partiendo del único dato conocido, que el campo admitía String y numerico, probamos con diversas entradas: letras, números, combinaciones alfanuméricas, caracteres especiales, otros idiomas, campos vacíos y espacios en blanco. Además, modificamos el ID en las solicitudes API para verificar la respuesta del sistema ante variaciones.

<h2 style="font-size:30px;">Proyecto: Booker  </h2>
Booker: El sistema admitía tres tipos de datos principales: string, numérico y booleano. Durante las pruebas, nos enfocamos en evaluar las diferentes funcionalidades de la API, como Auth, CreateToken, Booking, GetBookingIds, GetBooking, CreateBooking, UpdateBooking, PartialUpdateBooking, DeleteBooking, Ping, y HealthCheck.

El uso de la variabilidad del dato String fue clave para identificar un problema específico: aunque el usuario se creaba correctamente, no se generaba el token de autenticación, lo que impedía la correcta autorización en el sistema. Este hallazgo permitió enfocar nuestros esfuerzos en garantizar que la comunicación entre la API y los servicios backend fuera fluida. Además, evaluamos las respuestas y errores comunes que surgían a partir de datos incorrectos o incompletos, asegurando que la API gestionara correctamente todos los tipos de entradas y respondiera de forma consistente en escenarios de prueba.

<h2 style="font-size:30px;">Proyecto: Bugbank  </h2>
A diferencia de los proyectos anteriores, este fue una aplicación web con mayor complejidad debido a la interacción directa del usuario y la necesidad de proteger los movimientos financieros y la seguridad de los datos. Nos enfocamos principalmente en garantizar una excelente experiencia de usuario, priorizando la protección de los bienes financieros y la integridad de la información. Las pruebas también se centraron en evaluar la capacidad de respuesta de la aplicación y asegurar la seguridad en la transferencia de información sensible, como datos personales y bancarios, asegurando que estos se gestionaran de manera adecuada en todos los procesos.


