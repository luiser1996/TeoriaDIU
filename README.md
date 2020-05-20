# Trabajo de Teoria de Diseño de Interfaces de Usuario
ErrantT, plataforma de coworking. Curso: 2019/20

Autor:
* :bust_in_silhouette:   Luis Escobar Reche. 77142368T.

Logotipo: 

![Logo](img/Logo.jpg)

----- 

En este caso analizare una plataforma de coworking y realizare una propuesta para su diseño Web/movil. Utilizare herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 

Coworking es una forma de trabajo que permite a profesionales independientes, emprendedores, y pymes de diferentes sectores, compartir un mismo espacio de trabajo, tanto físico como virtual, para desarrollar sus proyectos profesionales de manera independiente, a la vez que fomentan proyectos conjuntos. Esto les permite compartir oficina y equipamientos, y constituye una propuesta más elaborada que por ejemplo los cibercafés, entornos en los que también se cuenta con conexión a internet.


# Proceso de Diseño 

## Paso 1. Desk Research & Analisis 

1.a Analisis Competitivo
-----
En el ámbito del coworking existen muchos sitios que ofrecen este servicio, pero no existe una aplicación o web que destaque sobre el resto, todas son bastante pobres. [ErrantT](https://www.errant.es/es/) es una página web que nos da información sobre el area de trabajo que ofrecen en Granada centro, a parte de esto solo nos permite mandar un formulario de contacto y poco mas. El motivo por el cual he elegido esta pagina es por que carece de
muchas funcionalidades que considero que se pueden implementar, como por ejemplo permitir check-in virtual, salas de reuniones virtuales, soporte en varias plataformas y que sobre todo tenga un diseño intuitivo y fluido, para que pueda atraer a clientes. Otras aplicaciones o paginas ofrecen un mejor diseño pero siguen sin aportar estas funcionalidades.

1.b Mapa de empatia del usuario
---- 
![Mapa de empatia](img/mapaEmpatia.png)

1.c Analisis de Usabilidad
---- 
 - Enlace al documento: 
[Revisión de usabilidad](templates/analisisUsabilidad.pdf)
 - Valoración final:
54/100
 - Comentario sobre la valoración:  
Después de valorar cada apartado de la plantilla y tras comentar algunos apartados, la puntuación final es de 54/100. La justificación de esta nota es que en general esta aplicación es muy incompleta, ofrece pocas funciones y poca ayuda online. En cuanto a rendimiento y diseño visual no esta mal, ofrece las características mas básicas de las habituales en una aplicación web.

## Paso 2. UX Design  

2.a Feedback Capture Grid
----
Mi propuesta de aplicación para coworking se llama WorkHard.
Consiste en una app para el móvil a corto plazo aunque se planea ampliar a otras plataformas a largo plazo.
Sus principales funciones y lo que la diferencia del resto es que hace la experiencia de las páginas para compartir viaje más fácil. Esto se consigue ya que consiste en un buscador como el de un buscador de vuelos u hoteles, en el que introduces unas fechas y un origen y destino. La búsqueda devuelve tres opciones; vuelos, hoteles o grupos de viaje. La parte de vuelos y hoteles es como cualquier comparador de vuelos, en el que reservas directamente tu vuelo comparándolo para buscar el que más te convenga. El añadido es los grupos, que actúan como grupos de cualquier red social, en el que alguien crea un grupo y los que buscan grupos de viaje solicitan acceso a él, tras tener acceso pueden ver los perfiles de los integrantes y elegir entrar definitivamente o no. Además hay un sistema de puntuación para dar valoraciones negativas o positivas a los compañeros de viaje. También se pueden marcar como favoritos vuelos hoteles o grupos para compararlos más tarde, además las tres cosas actúan como un paquete a la hora de reservar, de tal forma que en el apartado de reservas tengas tu viaje y te indique el vuelo hotel y grupo que has elegido.

![Malla](P2/Malla.jpg)

![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
-----
En el sitemap hemos añadido:
Index.html: Será la página principal.
Favoritos.html: Contendrá los viajes, alojamientos o grupos que desee guardar el usuario.
Reservas.html: Contendrá las reservas que tiene confirmado el usuario, tanto vuelos como alojamientos, cada uno de ellos contendrá toda la información asociada a la reserva.
Mensajes: En esta página el usuario podrá compartir mensajes con otro viajante o otro grupo de viajantes.
Perfil.html: En esta página se almacenará toda la información asociada al usuario.
About.html: En esta página se almacenará toda la información acerca de la empresa y que sea de interés para los usuarios.
Ayuda.html: En esta página se almacenará información como preguntas frecuentes, etc. Cualquier tipo de ayuda para el usuario, además se le proporcionará información para que pueda contactar con el equipo de ayuda.
![sitemap](P2/sitemap.png)

Es esta tabla se ve que tareas se ejecutan con más frecuencia para distintos grupos de usuarios, en gris se marcan las tareas más importantes.
Consideramos estas tareas más importantes basándonos en que si estas funciones fallaran, la aplicación sería un fracaso, en cambio si fallan las otras seguiría siendo un gran fallo pero no un fallo crítico.
Se puede observar que las tareas de grupos, chat, redes sociales y el buscador las usan más los jóvenes y en cambio las tareas de reservar las usan más la gente mayor.

![matriz](P2/Matriz.jpg)

![Método UX](img/labelling.png) 2.c Labelling 
----
Hemos utilizado iconos que son muy utilizados hoy en dia en cualquier tipo de aplicación y creemos que no confundirán al usuario. En el caso de la página principal un ícono de una casa, en la sección favoritos un corazón, en la reservar un ícono de un libro, en los mensajes una viñera simulando un comentario, en el perfil un ícono de una persona, en about un icono de i, como de información y ya por ultimo de ayuda un icono de una interrogación.

[Labelling](P2/Labelling.pdf)

![Método UX](img/Wireframes.png) 2.d Wireframes
-----
Para el desarrollo de bocetos nos hemos centrado en dispositivos móviles, el boceto consta de varias partes:
Pantalla principal: En ella se detallan las búsquedas que desee realizar el usuario concretando el número de viajeros, la fecha, el origen y el destino. Además podrá ver los destinos populares, las fotos publicadas por los usuarios en sus redes sociales y las redes disponibles de la aplicación. Por último también dispondrá de un botón para acceder a los ajustes, y en la parte inferior un pequeño menú para acceder a las distintas secciones de nuestra aplicación.
Ajustes: En esta sección el usuario podrá configurar la aplicación, como activar/desactivar el modo oscuro, activar/desactivar las notificaciones, cerrar sesión, etc.
Búsquedas: Esta sección será la resultante de realizar una búsqueda en la pantalla principal, en ella se concretarán información de la búsqueda y además se mostrará todos los resultados obtenidos.
Favoritos: En esta sección el usuario almacenará todos los vuelos, alojamientos, grupos que desee guardar para poder ver en otro momento. Con esto se busca ofrecer una mejor experiencia al usuario para cuando desee guardar un viaje para el futuro. Así el usuario tenga acceso directo al viaje guardado en un futuro.
Mensajes: En esta sección de la aplicación el usuario podrá compartir mensajes con otros viajeros o con algún grupo de viaje.
Perfil: En esta sección el usuario podrá ver su información personal y la que está de forma visible a todos los demás usuarios. Además podrá subir algunas fotos, los demás usuarios podrá insertar comentarios en su perfil y este contestar a estos cuando desee. Además podrá introducir información de viajes que haya realizado. 
Reservas: En esta sección se encuentran todas las reservas del usuario, tanto de viajes como de alojamientos. En ella se almacenan todo tipo de información asociado al viaje o al alojamiento.

[Bocetos](Bocetos.pdf)

![Método UX](img/landing-page.png)  2.e Logotipo
----
![Logo](img/Logo.jpg)

He usado para diseñarlo la herramienta [TailorBrands](https://www.tailorbrands.com/es/logo-maker). Esta herramienta es gratis pero se necesita la version pro para guardar los logos en varias resoluciones.

![Método UX](img/guidelines.png) 2.f Guidelines
----

Como tipografía principal de la aplicación hemos decidido optar por una tipografía moderna, sencilla y que sea perfectamente legible: Roboto. Roboto es una fuente de uso libre de Google Fonts. Esta tipografía la podemos combinar con otra tipografía como por ejemplo Open Sans, la cual es también muy utilizada, de uso libre y desarrollada por Google Fonts. Por tanto como tipografía principal empleamos Roboto y como tipografía secundaria Open Sans. Respecto al tamaño de fuente hemos decidido seguir los estándares, para Roboto se recomienda usar un tamaño de 14-18px para el contenido principal mientras que para las cabeceras un tamaño de 28-34px. Respecto a Open Sans también seguimos los estándares, es decir, utilizar un tamaño de 12-16px para contenidos principales y un tamaño de 24-30px para cabeceras.
A continuación adjunto un par de imágenes de cada tipo de fuente:

Roboto:
![roboto](P3/roboto.png)

Open Sans:
![opensans](P3/opensans.png)

-Fuente de las imágenes: https://medium.muz.li/top-5-ui-fonts-for-website-mobile-apps-d78829e58f7e

Respecto a los colores que vamos a utilizar en nuestra página hemos optado por unos colores básicos para no generar confusión a los usuarios cuando usan nuestra aplicación y no se encuentren colores llamativos o incluso colores que molesten a la vista, un ejemplo perfecto de colores que queremos emplear:

Color de letra: Negro
Color de Títulos: Negro
Color de cabeceras y Barra de navegación inferior: Negra
Títulos en las cabeceras o en las barras de navegación: Blanca

Nuestro objetivo es jugar con el blanco y el negro, proporcionando así una aplicación que emplea colores básicos y que pretende dar gran importancia a su contenido. Por tanto, el objetivo principal y por el cual usamos estos colores básicos es conseguir que el usuario se vea más impresionado por el contenido de nuestra aplicación como imágenes de lugares a los que viajar, imágenes compartidas por usuarios, etc. Un ejemplo para ilustrar el camino por el que queremos orientar nuestra aplicación:

![colores](P3/colores.png)

-Fuente de la imagen: 
https://material.io/design/color/applying-color-to-ui.html#typography-and-iconography 

Respecto a los patrones:

En primer lugar, como patrón de organización de la información hemos decido implementar el patrón combinado: Destacado/Buscar/Navegar porque combina varios estilos para organizar la información y nos viene perfecto porque además de mostrar información al usuario queremos añadir buscadores para mejorar la experiencia del usuario. Además, cuando un usuario se encuentre navegando puede realizar una búsqueda de forma sencilla sin tener que cambiar de localización dentro de la app.

Cuando se realice un usuario quiera realizar una búsqueda vamos a introducir técnicas de autocompletado y cuando se obtengan los resultados también introduciremos la opción de filtrar los resultados.

En relación a la organización de las imágenes queremos organizar las imágenes en forma de carrusel, creemos que es la forma más utilizada en la actualidad y al usuario le resultará familiar, sabrá utilizar el carrusel. No buscamos proporcionar dificultades ni problemas al usuario durante el uso de nuestra app, luego el uso de estilos/iconos/herramientas ya implementadas por muchas aplicaciones hoy en día nos ayuda a conseguir este objetivo pues el usuario ya está familiarizado a ello. Por último, aclarar que cada una de las imágenes tendrán disponibles las opciones de ampliar la imagen, volver a la anterior imagen, e ir a la siguiente imagen. 

Para el patrón de navegación hemos de decidido implementar la navegación con tabuladores en la parte inferior de nuestra App. La navegación con tabuladores en las aplicaciones móviles ha ido adquiriendo gran importancia y es bastante utilizada pues proporciona una navegación fluida entre las diferentes secciones de nuestra App. Además, es bastante intuitiva pues cuenta con iconos y una pequeña descripción que ayudan al usuario a entender cada una de las secciones disponibles, adjunto un pequeño ejemplo de navegación con tabuladores en Apps:

![patrones](P3/patrones.png)

Fuente de la imagen: 
https://dribbble.com/shots/7057842-Tab-bar-menu-navigation

## Conclusión

En general al realizar un estudio acerca de los tres proyectos propuestos por el profesor, hemos llegado a la conclusión de que crear personas ficticias coherentes y que representen a una persona cualquiera hoy en dia es importante, ya al fin y al cabo las personas normales y comunes son las que llegarán a utilizar nuestra aplicación, luego crear una persona ficticia poco coherente no tendría ninguna aportación positiva en el desarrollo de nuestro proyecto. 
Por otro lado, también hemos llegado a la conclusión de que crear buenos bocetos es esencial para que otra persona pueda comprender nuestro proyecto y además nos ayuda a encontrar posibles errores o elementos ambiguos que afectarán de mala manera a nuestra aplicación. Además, si se realizan de forma clara y correcta ayudarán a ver si nuestro proyecto avanza en buen camino. 
Por último, también creemos que desarrolar un buen user journey map es de gran importancia pues nos ayudará a estudiar posibles acciones y dificultades que encuentra un usuario a la hora de buscar nuestra aplicación o a la hora de usar nuestra aplicación. Un ejemplo perfecto es el caso de museMapp en el que gracias al user journey map se consiguió obtener información importante acerca del comportamiento de las personas, sobre cual sería la mejor forma de acercar la aplicación a ellos y que les sea muy facil de utilizar.






