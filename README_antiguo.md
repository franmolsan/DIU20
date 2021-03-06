# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa)

Grupo: DIU2.MAF.  Curso: 2019/20

Proyecto:

Descripción:

Logotipo:

Miembros
 * :bust_in_silhouette:  Francisco José Molina Sánchez     :octocat:  
  [@franmolsan](https://github.com/franmolsan)
 * :bust_in_silhouette:  Miguel Ángel Molina Jordán     :octocat:  
  [@MangelMolina](https://github.com/MangelMolina)

-----

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist)


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online.


# Proceso de Diseño

## Paso 1. UX Desk Research & Analisis

![Método UX](img/Competitive.png) Competitive Analysis
-----

### ALTERNATIVA 1: BADI
<https://badi.com/es/>  
Cuenta con una guía de uso en la página principal.
Buscador fácil de utilizar y muy completo, con opciones para ajustarse al presupuesto, número  de compañeros, etc.
Muestra mucha información de cada alojamiento: fotos, ubicación, disponibilidad, estancia mínima, compañeros de piso, tamaño de la habitación o piso, comodidades (calefacción, tv, etc.), entre otras.

### ALTERNATIVA 2: COUCHSURFING
<https://www.couchsurfing.com/>  
No permite buscar alojamientos directamente, antes necesitas registrarte.
La páginas de términos y condiciones, ayuda y contacto  están en inglés directamente, no en español.
Una vez que te registras, ya puedes buscar alojamientos, grupos, eventos, etc. Aunque tiene muchas funcionalidades, es compleja en comparación con las otras alternativas y un poco confusa; hay demasiada información a la vez.

### ALTERNATIVA 3: COMPARTE TU PISO
<https://compartetupiso.com/>  
No permite buscar alojamientos antes de registrarse (igual que couchsurfing).
Tiene muchos problemas: aunque tengamos la sesión iniciada, el botón de iniciar sesión sigue apareciendo, una vez que se cierra la sesión que se crea al registrarse  no se puede iniciar porque la página de inicio de sesión está incompleta (no tiene ni formulario); no se puede buscar (o al menos no fácilmente), etc.

![Iniciar sesión incompleto](P1/ComparteTuPisoLogin.JPG "No se puede iniciar sesion")

### ALTERNATIVA 4: PISO COMPARTIDO
<https://www.pisocompartido.com/>  
Puedes ver los pisos que disponibles antes de registrarte en la página.
El buscador está muy completo y tiene muchas opciones para buscar, aunque debería poderse filtrar por la edad de los compañeros. Al igual que badi, tiene mucha información sobre cada alojamiento.


Hemos seleccionado Couchsurfing ya que parece que tiene un buen diseño, pero comparandola con las otras opciones, es más compleja y creemos que todavía tiene margen de mejora.

![Método UX](img/Persona.png) 1.b Persona
-----
Hemos seleccionado a estas personas porque son perfiles muy distintos, pero a la vez son posibles usuarios de CouchSurfing.
- Josefina está divorciada, sus hijos no pueden acompañarla  y no tiene amigos que viajen, por lo tanto tiene que hacer los viajes sin que nadie la acompañe. Por ello, podría utilizar CouchSurfing para tener compañia y no sentirse sola en sus viajes.

- Mario es estudiante y no dispone de suficiente dinero, por lo que CouchSurfing es una alternativa a los viajes convencionales para ahorrar y seguir viajando. Además Mario estudia Traducción e Interpretación, por lo que le gusta mucho conocer a los nativos del lugar que está visitando e intentar aprender su idioma y costumbres.

![PersonaJosefina](P1/PersonaJosefina.jpg "Josefina")
![PersonaMario](P1/PersonaMario.jpg "Mario")  

[Ficha Josefina](P1/PersonaJosefina.jpg "Josefina")  
[Ficha Mario](P1/PersonaMario.jpg "Mario")  

![Método UX](img/JourneyMap.png) 1.c User Journey Map
----
Hemos escogido estas experiencias de usuario porque reflejan la complejidad de la página:
- La experiencia de Josefina es negativa, porque hay demasiadas opciones en la página y tiene que introducir muchos datos para completar su perfil y poder hablar con anfitriones. Además, no le gustó que algunos elementos de la página estuvieran en inglés, como la ayuda o la búsqueda.
- La experiencia de Mario fue positiva, ya que consiguió contactar con un anfitrión en Polonia con el que llegó a un acuerdo para alojarse, aunque le pareció incómodo tener que introducir tanta información antes de poder hablar con los anfitriones.

![Journey Josefina](P1/JourneyJosefina.jpg "Josefina")  
![Journey Mario](P1/JourneyMario.jpg "Mario")  

[Journey Josefina](P1/JourneyJosefina.jpg "Josefina")  
[Journey Mario](P1/JourneyMario.jpg "Mario")

![Método UX](img/usabilityReview.png) 1.d Usability Review
----

[Documento de revisión de usabilidad](P1/UsabilityReviewCouchsurfing.pdf)  
Valoración final: 83 - Buena.  
La nota que ha obtenido Couchsurfing en el usability review es de 83. En general la página funciona correctamente y se merece buena nota.  
El mayor problema que hemos encontrado es la experiencia para un usuario nuevo. Cuando entra por primera vez a la página, ha de registrarse para poder buscar un alojamiento. Una vez que el usuario se ha registrado y accede a la página principal, le puede resultar compleja porque tiene muchas opciones, sobre todo si la comparamos con las otras alternativas (Badi, piso compartido). Tampoco ayuda mucho la página, no da un tour o un tutorial sobre como usarla. Si el usuario busca la ayuda, solo la va a encontrar en inglés, por lo que tiene que superar la barrera del idioma.  
Otro problema que tiene es la cantidad de información personal que el usuario nuevo ha de introducir para interactuar con otros usuarios. Ha de explicar sus gustos, los idiomas que habla, los países que ha visitado, un breve biografía, etc. Es quizás demasiada información para un usuario que acaba de llegar y no ha usado la página.
Realmente, una vez que el usuario se familiariza con la página, es bastante sencilla y funciona como uno se espera.





## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid
----


>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior,


| Interesante | Críticas   |
| ------------- | ------- |
| <ul><li>Dispone de diversas funcionalidades aparte de planificar una estancia, centradas en la comunicación entre usuarios: eventos, grupos, mensajes, etc.</li><li>Recomienda a los usuarios posibles destinos para viajar, indicando el número de anfitriones que hay en cada lugar</li><li> El buscador es completo y está disponible en todas las páginas.</li></ul> | <ul><li>En la web el buscador funciona solo en inglés. En la aplicación móvil también funciona en español (pero le da prioridad al inglés).</li><li>Los elementos de ayuda y más información solo están disponibles en inglés (tanto en la web como en la aplicación móvil)</li><li>No se pide confirmación al añadir una información, ni se puede deshacer fácilmente.</li><li>Para acceder a la página web y poder ver las funcionalidades que ofrece hay que registrarse.</li><li>Hay que introducir demasiados datos para interactuar con otros usuarios, reservar alojamiento, etc.</li></ul>|




| Preguntas | Nuevas ideas |
| ------------- | ------- |
|<ul><li>Poner la ayuda y la búsqueda en español.</li><li>Poder ver las funcionalidades antes de registrarse.</li><li>¿Por qué es necesario introducir tanta información “irrelevante” (como los hobbies, los libros que más me han gustado,...) para poder contactar con un anfitrión?</li></ul> | <ul><li>Realizar un tutorial rápido cuando el usuario se registre, para mostrarle las diferentes funcionalidades que ofrece la página.</li><li>Ofrecer páginas de ayuda y preguntas frecuentes en español además de inglés.</li><li>Dar al usuario la posibilidad de deshacer sus acciones y pedir confirmación para las acciones más importantes.</li><li>Añadir un apartado de consejos para viajes, que nos explique la cultura del lugar de destino, documentación que necesitemos, números de emergencias, etc.</li></ul>|


>>> ¿Que planteas como "propuesta de valor" para un nuevo diseño de aplicación para economia colaborativa ?
>>> Problema e hipótesis
>>>  Que planteas como "propuesta de valor" para un nuevo diseño de aplicación para economia colaborativa te
>>> (150-200 caracteres)

Como propuesta de valor se nos ha ocurrido añadir un tutorial que muestre a los usuarios más novatos las distintas funcionalidades que ofrece el sistema en detalle y de una forma sencilla. Así, cuando un usuario se registre y acceda por primera vez al sistema, no resultará abrumado por todas las opciones que se muestran en el menú y en la pantalla principal.

También traduciremos las páginas de ayuda, soporte, preguntas frecuentes, etc. a español. Aunque Couchsurfing se basa en una comunidad internacional y tiene muchos usuarios que dominan el inglés, creemos que elementos tan básicos como la ayuda deberían estar disponibles en español.

Asimismo añadiremos una nueva funcionalidad para que los usuarios puedan compartir información sobre los diferentes destinos: avisos, consejos y recomendaciones sobre la documentación, medios de transporte recomendados, información sobre las autoridades, leyes, costumbres importantes, festividades, etc. En esta nueva funcionalidad también proponemos añadir un apartado de noticias, eventos o avisos importantes relacionados con los viajes en el destino (por ejemplo, informar de que ya no se puede viajar a un país debido a que ha cerrado sus fronteras).


![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap
-----

>>> Definir "User Map" y "Task Flow" ...



User/task matrix:

![User/task matrix)](P2/UserTaskMatrix.jpg) 

Hemos elegido la matriz de tareas ya que nos permite representar la importancia de cada tarea para cada grupo de usuario y por lo tanto se adapta mejor a las nuevas propuestas que hemos hecho. También nos permite destacar las tareas que son más críticas e importantes, que son:
* Acceder a la ayuda, ya que es clave que los usuarios novatos puedan consultarla de una manera sencilla.
* Deshacer acciones, para evitar errores a la hora de mandar mensajes, escribir comentarios, etc.
* Crear consejo, porque es la funcionalidad más importante del sistema de consejos que hemos creado. Si los usuarios no pueden crear consejos de una forma fácil, no se  verán incentivados a crearlos, por lo que habrá pocos consejos y este sistema no se utilizará mucho.



Sitemap:


![sitemap](P2/sitemap.jpg)



[Sitemap (pdf)](P2/sitemap.pdf) 


![Método UX](img/labelling.png) 2.c Labelling
----


>>> Identificar términos para diálogo con usuario  

![labelling1](P2/labelling1.jpg)
![labelling2](P2/labelling2.jpg) 
![labelling3](P2/labelling3.jpg) 
![labelling4](P2/labelling4.jpg) 
![labelling5](P2/labelling5.jpg)
![labelling6](P2/labelling6.jpg) 

![Método UX](img/Wireframes.png) 2.d Wireframes
-----

>>> Plantear el  diseño del layout para Web/movil (organización y simulación )

[Bocetos (pdf)](P2/BocetoLofi.pdf)

Boceto del Panel (pantalla principal)


![Boceto del Panel (pantalla principal)](P2/BocetoPanel.jpg) 

Boceto del Menú


![Boceto del Menú](P2/BocetoMenu.jpg) 

Boceto de la página de consejos


![Boceto de la página de consejos](P2/BocetoListaConsejos.jpg) 

 Boceto de la vista de un consejo

![Boceto de la vista de un consejo](P2/BocetoConsejo.jpg)

Boceto de la página para añadir un nuevo consejo


![Boceto de la página para añadir un nuevo consejo](P2/BocetoNuevoConsejo.jpg)

 Boceto del menú para confirmar el envío de un consejo

 
![Boceto del menú para confirmar el envío de un consejo](P2/BocetoConfirmacionEnvio.jpg)

Boceto del menú para descartar un consejo


![Boceto del menú para descartar un consejo](P2/BocetoDescartar.jpg) 

Boceto de la página de ayuda


![Boceto de la página de ayuda](P2/BocetoAyuda.jpg) 


En el panel (que es la página principal), se muestra un menú rápido para buscar, eventos cercanos, mensajes y comentarios nuevos, etc.
Hemos creado un menú que se despliega y se esconde para que el usuario disponga de una visión más limpia del contenido, pero sin perder las funcionalidades del menú.


Los consejos se buscan dependiendo de una ubicación y se pueden filtrar por nuevos, más votados, etc. Cuando seleccionas un consejo, puedes ver el título, el texto, las imágenes, los comentarios asociados y los votos que este ha recibido.
A la hora de escribir un nuevo consejo, hay que añadir un título, un texto, las etiquetas (tags), y opcionalmente se pueden añadir imágenes. Estas pueden subirse tanto de la cámara como de la galería. 


Hemos añadido también un menú para confirmar que el usuario quiere enviar o descartar un consejo, lo cual reduce las posibilidades de que el usuario pueda enviar o descartar un consejo accidentalmente. Esta funcionalidad podría estar también en otras páginas del sistema, como en los eventos y mensajes.


En la pantalla de ayuda hay varias opciones: acceder un tutorial para entender las funcionalidades de la página, información sobre el uso de la aplicación móvil,  información sobre couchsurfing, consejos e información relativa a la seguridad y realizar una pregunta a un administrador de la página o un moderador.


## Paso 3. Make (Prototyping)


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard)

![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


## Paso 4. UX Check (Usability Testing)


![Método UX](img/ABtesting.png) 4.a A/B Testing
----


>>> Comprobacion de asignaciones para A/B Testing. Asignaciones https://github.com/mgea/DIU19/blob/master/ABtesting.md

>>>> Práctica A:


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Usuarios para evaluar prácticas


| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal


![Método UX](img/usability-report.png) 4.c Usability Report
----

>> Añadir report de usabilidad para práctica B



## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report
----

>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG)



## Conclusión / Valoración de las prácticas


>>> (90-150 caracteres) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  
