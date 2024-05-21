# DIU24
Prácticas Diseño Interfaces de Usuario 2023-24 (Tema: Grupos de Teatro ) 

Grupo: DIU1_bigotessucios.  Curso: 2023/24 
Updated: 19/3/2024

Proyecto: 
**MesaManía**

Descripción: 

_Somos un club de juegos de mesa que se junta de forma habitual en nuestro propio recinto. Realizamos demostraciones de juegos, torneos de cartas y otros juegos, además de contar con nuestra propia tienda.
Por otra parte, ofrecemos un servicio de alquiler de salas de juego, que incluye el propio espacio y una gran variedad de juegos de mesa. Contamos con un sistema de socios que permite una fácil inscripción a las actividades del club y otras ventajas._
 

Logotipo: 
>>> Opcionalmente si diseña un logotipo para su producto en la práctica 3 pongalo aqui

Miembros
 * :bust_in_silhouette:  Pedro Benitez Gris    :octocat:     
 * :bust_in_silhouette:  Carlos Muñoz Barco    :octocat:

----- 

# Proceso de Diseño 

## Paso 1. UX User & Desk Research & Analisis 


![Método UX](img/Competitive.png) **1.a User Reseach Plan**
-----

Como objeto principal de esta práctica hemos escogido la página web de [La Estupenda](https://espaciolaestupenda.com/) . Poniendonos en la piel de los dueños del club de teatro hemos podido encontrar puntos de mejora y objetivos que nos interesaría conseguir a largo plazo y así definir de una forma mas clara estas areas de mejora. Para ello, hemos realizado este [User Research Plan](P1/UserResearchPlan.pdf).

![Método UX](img/Competitive.png) 1.b Competitive Analysis
-----

![Competitive Analysis](img/Competitor.png)

Para este analisis de los competidores hemos elegido [La Carpinteria Teatral](https://lacarpinteriateatral.com/) y [Tengo Teatro](https://www.tengoteatro.com/) para contrastarlos con la página de La Estupenda. Hemos escogido la Carpinteria Teatral por ser granadina, 
lo que nos permite comprarar La Estupenda con otra compañia de teatro en su mismo contexto, y Tengo Teatro por ser una
compañia de teatro bastante reconocida, lo que nos permite comparar La Estupenda con otra compañia que, en principio, hace las cosas "bien".
Es facil observar que las dos compañias granadinas están bastante igualadas, pero La Estupenda sale ganando por poco. Sin embargo, ambas son considerablemente deficientes comparadas con Tengo Teatro, donde el presupuesto superior se refleja notablemente en su página web.
Si tuvieramos que destacar los puntos fuertes de cada una serían: en el caso de La Estupenda, el precio, pues es el que ofrece
los servicios mas baratos, para La Carpinteria Teatral el diseño, que pese a no ser particularmente eficaz si es destacablemente
atractivo, mientras que Tengo Teatro dispone del diseño mas intuitivo y la mayor facilidad de uso.

![Método UX](img/Persona.png) 1.c Persona
-----

Para esta parte nos hemos encargado de crear dos personas ficticias para entender como puede ser una persona normal que puede ser usuario de nuestra página. Para ello hemos creado un chico, Javier Martos, y una chica, Chessie Chesster, ambos jovenes que buscan algo nuevo que hacer, uno por unas razones diferentes a las del otro. Por una parte, Javier Martos es una persona joven e inmadura pero que consta con una motivación bastante sólida. Por otra parte, Chessie Chesster es una persona mas centrada pero que tiene como única motivación ocupar su tiempo libre.

![Javier Martos](img/Javier.png)
![Chessie Chesster](img/Chessie.png)

![Método UX](img/JourneyMap.png) 1.d User Journey Map
----
![Journey Map Javier Martos](img/Javier-Journey.png)
![Journey Map Chessie Chesster](img/Chessie-Journey.png)

Hemos escogido estas experiencias porque nos hemos dado cuenta que para el usuario normal no acaba resultando tan intuitivo ni atractivo realizar ambas tareas, que a nuestro parecer, deben de ser las más comunes en cuanto a un grupo teatral. En ambos casos los dos personajes se encuentran con numerosos 
contratiempos fruto de la falta de funcionalidades que faciliten la experiencia de usuario (como la falta de una opción de compartir un curso por redes sociales) o de la pobre implementación de las que si son ofrecidas por la página web (como la falta de descripción en los cursos fuera de la página asociada a cada uno de ellos).

![Método UX](img/usabilityReview.png) 1.e Usability Review
----
En la [Usability Review](P1/UsabilityReview.pdf) podremos ver una revisión objetivo de muchos de los aspectos de la página web donde hemos obtenido una valoración final de **53** puntos sobre 100, que según la valoración, los usuarios deberian de poder completar la mayoria de sus objetivos a pesar de carecer de una buena experiencia de usuario.

A forma de resumen, probando y analizando la página web de “La Estupenda”, pudimos encontrar áreas de mejora en esta. El User Research nos reveló que varias acciones en la página web no eran tan intuitivas, además de no llegar a ser tan atractiva y persuasiva como otras páginas que pudimos comparar en el Competitor Analysis. La creación de dos personas ficticias nos ha ayudado a ver que no solo es un usuario idealizado el que querrá hacer uso de la web, sino también a comprender las expectativas y necesidades de una persona normal al utilizar la web. Y el usability review nos ha permitido ver de forma objetiva los numerosos fallos y carencias que la página web tiene.

## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
----

Primero hemos realizado un mapa de empatía respecto a lo que un usuario normal puede sentir al respecto de nuestra propuesta

![Empathy Map](img/empathy_map.png)
  
Nuestra propuesta de valor para un nuevo diseño es crear una aplicación web que muestre de forma legible y fluida la información que el usuario espera encontrar, creando además llamadas de acción a participar en el club e involucrarse aun más

![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----
Para nuestro club, hemos realizado este scope canvas para definir en que consiste nuestro proyecto
![Método UX](img/scope_canvas.png)

![Método UX](img/Sitemap.png) 2.b User Flow (task) analysis 
-----

El user Map sirve para mostrar de forma visual las interacciones y caminos que un usuario puede tomar dentro de nuestra plataforma. Mientras que el task analysis nos ayudará a identificar las tareas principales y su relevancia para los
usuarios:

| Grupos de usuarios                | Jugadores competitivos | Jugadores aficionados | Principiantes / Personas que están empezando el hobby | Personas que quieren hacer amigos | Coleccionistas |
| --------------------------------- | ---------------------- | --------------------- | ----------------------------------------------------- | --------------------------------- | -------------- |
| Alquilar salas                    | M                      | H                     | L                                                     | L                                 | L              |
| Comprar juegos de mesa            | L                      | M                     | H                                                     | M                                 | H              |
| Apuntarse en torneos              | H                      | M                     | L                                                     | M                                 | M              |
| Intercambiar juegos de mesas      | L                      | H                     | M                                                     | M                                 | H              |
| Descubrir y probar juegos nuevos  | L                      | H                     | H                                                     | M                                 | H              |
| Empezar un nuevo hobby            | L                      | L                     | H                                                     | M                                 | L              |
| Asistir a eventos                 | H                      | H                     | H                                                     | H                                 | H              |
| Jugar partidas con otros miembros | H                      | H                     | H                                                     | H                                 | M              |

El user flow nos muestra los flujos muestran de forma visual la acciones que hay que llevar a cabo para realizar una actividad/tarea, y muestra las relaciones y las dependencias entre las mismas:

![Método UX](img/user_flow.png)


![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----
![Sitemap](img/sitemap.png)
 

| Término                      | Significado                                                     |
| ---------------------------- | --------------------------------------------------------------- |
| Unete al Club                | Ir al formulario de inscripción al club                         |
| Alquiler de salas            | Realizar una reserva online de una sala para jugar              |
| Torneos                      | Torneos de juegos de mesa                                       |
| Crear tu propio Torneo       | Formulario de información del torneo a crear por el usuario     |
| Unirse a un torneo existente | Formulario de inscripción a un torneo creado por otro usuario   |
| Conseguir Juegos de mesa     | Apartado de compra y cambio de juegos de mesa                   |
| Comprar juego de mesa        | Adquirir a traves del club juegos de mesa                       |
| Intercambiar juegos de mesa  | Prestar juegos de mesa a cambio de otros                        |
| Eventos                      | Eventos de juegos de mesa                                       |
| Organizar evento             | Crear un evento para una fecha determinada                      |
| Consultar eventos proximos   | Consultar los eventos próximos organizados por otros miembros   |
| Contacto                     | Pagina con informacion de contacto                              |


![Método UX](img/Wireframes.png) 2.d Wireframes
-----

![Catalogo](img/CatalogoJuegos_portatil.png)
![Catalogo](img/CatalogoJuegos_tablet.png)
![Catalogo](img/CatalogoJuegos_movil.png)
![Catalogo](img/JuegoDetalle_portatil.png)
![Catalogo](img/JuegoDetalle_tablet.png)
![Catalogo](img/JuegoDetalle_movil.png)



## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard_icono.png) 3.a Moodboard
-----

A continuación se muestra el moodboard usado para la realización del proyecto. Incluye:
<ul>
  <li>Nuestra imagen de marca</li> 
  <li>Nuestro logo final</li>
  <li>Todos los logos utilizados</li>
  <li>La paleta de colores.</li>
  <li>la tipografía</li>
  <li>Imágenes de como serán los eventos e imágenes del estilo de la página</li>
</ul>

![Método UX](img/moodboard.png)



![Método UX](img/landing-page.png)  3.b Landing Page
----
Nuestra Landing page tiene como objetivo mostrar al usuario todo lo que tenemos para ofrecer de forma clara y concisa.
Mostramos mediante una tarjeta y un texto descriptivo las 3 principales actividades del club e incitamos al usuario a unirse al club mediante call to actions y botones llamativos para apuntarse.
![LandingPage](img/landing_page.png)


![Método UX](img/guidelines.png) 3.c Guidelines
----
Los patrones usados en el diseño de la aplicación han sido los siguientes:

<ul>
  <li>Onboarding: pagina principal que ve un usuario al entrar en la aplicación.</li> 
  <li>Menu: menu lateral adaptado a movil para navegar por las distintas páginas de nuestra app.</li>
  <li>Carousel: carousel para mostrar las principales actividades ofrecidas por el club.</li>
  <li>Search: una barra de búsqueda para acceder de forma mas directa a cualquiera de las opciones de la aplicación.</li>
  <li>Article list: se muestra una lista de artículos mostrados como tarjetas.</li>
  <li>Item details: se muetra de forma detallada toda la información acerca de los juegos de mesa adquiribles por el usuario.</li>
 <li>Form imput: formulario para inscribirse en el club.</li>
 <li>About: una pequeña descripción acerca de quienes somos y que actividades llevamos a cabo. Además, se proporciona información acerca de se encuentra nuestro local fisicamente.</li>
 
</ul>

La pantalla de carga. Es lo primero que ve un usuario al entrar en la aplicación.
![Guidelines](img/PantallaPrincipal.png)

La pantalla principal. Muestra mediante tarjetas y la barra de navegación todas las funcionalidades que ofrece la aplicación.
![Guidelines](img/Principal.png)

La pantalla de registro. Sirve para unirse al club.
![Guidelines](img/registro.png)

La pantalla de torneos. Muestra los torneos que se celebrarán proximamente.
![Guidelines](img/eventos.png)

El catálogo de la tienda. Muestra los distintos juegos de mesa que se pueden comprar desde la aplicación, y la pantalla de compra de un juego en particular.
![Guidelines](img/catalogo.png)

La pantalla de información acerca del club. Ofrece información relevante para los usuarios como el e-mail de contacto o la localización de la sede del club.
![Guidelines](img/SobreNosotros3.png)


![Método UX](img/mockup.png)  3.d Mockup
----
El siguiente video muestra el funcionamiento de la aplicación. 
![](https://github.com/CarlosMunozBarco/DIU.bigotessucios/blob/master/img/mockup_mesamania.gif)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----

>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto


## Paso 5. Exportación & evaluación con Eye Tracking 

Exportación a HTML/Flutter
-----

![Método UX](img/eye-tracking.png))  5.b Eye Tracking method 

>>> Indica cómo diseñas experimento y reclutas usuarios (uso de gazerecorder.com)  

Diseño del experimento 
----

>> Uso de imágenes (preferentemente) -> hay que esablecer una duración de visualización y  
>> fijar las áreas de interes (AoI) antes del diseño. Planificar qué tarea debe hacer el usuario (buscar, comprar...) 


![experimento](img/experimentoET.png)  
>> cambiar img por tu diseño de experimento  

>> Recordar que gazerecorder es una versión de pruebas: usar sólo con 3 usuarios para generar mapa de calor (recordar que crédito > 0 para que funcione) 

Resultados y valoración 
-----



>> Cambiar por tus resultados
![Resultado](img/resultadoET.png)  



## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png) 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 





5.) Conclusion de EVALUACION (A/B testing + usability report + eye tracking) 
----


>> recupera el usability report de tu práctica (que es el caso B de los asignados a otros grupos) 
>> con los resultados del A/B testing, de eye tracking y del usability report:
>>  comentad en 2-3 parrafos cual es la conclusion acerca de la realización de la práctica y su evaluación con esas técnicas y que habéis aprendido






## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













