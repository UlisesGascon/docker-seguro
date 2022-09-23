# Introducción

Es importante remarcar, que este libro está orientado a un usuario medio/avanzado de Docker que ya tiene experiencia con el manejo de contenedores y con la creación de imágenes. 

Si aún no tienes esta experiencia, te recomiendo [el curso DOCKER DE NOVATO a PRO!](https://www.youtube.com/watch?v=CV_Uf3Dq-EU) de [Pablo Fredrikson ("Pelado Nerd")](https://github.com/pablokbs) y poner tus conocimientos en práctica antes de seguir la lectura.

Docker es una de las tecnologías más populares de los últimos años y es bastante probable que te tengas que enfrentar a crear imágenes y lanzar contenedores a lo largo de tu carrera.

Aunque es relativamente sencillo dar los primeros pasos en este universo y lanzar nuestro primer  `hello-world` con un solo comando `docker run hello-world`, estamos aún lejos de sentirnos cómodos poniendo nuestros contenedores en producción.

En los entornos actuales donde trabajamos con metodologías ágiles y seguimos una cultura [DevOps](https://es.wikipedia.org/wiki/DevOps), nos damos cuenta rápidamente, que no es suficiente con tener nuestro código listo. También tenemos que dar un paso más e involucrarnos en la parte operacional de la tecnología, entendiendo qué ocurre, una vez que publicamos nuestros cambios en el repositorio del equipo.

Si ya te has tenido que enfrentar a poner contenedores en producción o estás abstraído de la tarea con orquestadores como Kubernetes, este libro te ayudará a entender todo el margen de maniobra que se te ofrece con Docker para crear imágenes mucho más seguras y sólidas ([capítulo 3](c03.md)).

Así mismo, este libro te ayudará a comprender qué riesgos tenemos en cada fase del ciclo de vida ([capítulo 1.2](c01.md#12-los-pilares-de-docker)) y sobre todo qué herramientas ([capítulo 4](c04.md)) y técnicas podemos usar en nuestro día a día para desplegar contenedores sin miedo.

Docker lleva dando vueltas desde hace casi 10 años. En este tiempo, muchas veces hemos encontrado vacíos sobre cómo securizar las imágenes, y aunque existen muchos recursos accesibles, suelen estar desperdigados y ser muy dogmáticos.

He querido condensar mi experiencia con Docker en un libro sencillo y ameno, de fácil lectura.

Veremos cómo resolver muchas situaciones cotidianas en entornos productivos, sin intentar dogmatizar sobre qué camino es mejor o peor, nos centraremos en entender los riesgos y mitigaciones para que tu saques tus propias conclusiones adaptadas a tus necesidades y experiencia.

Espero que disfrutes de la lectura de este libro, tanto como yo he disfrutado al escribirlo.
