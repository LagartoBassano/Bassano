0. Nota introductoria del autor

    Antes de comenzar de lleno con el proyecto, considero prudente aclarar por adelantado algunos detalles que pueden causar dudas.
    Para empezar, decidí realizar el proyecto por mi cuenta por motivos de carácter personal. Dichos motivos me imposibilitaron el comenzar el proyecto de forma temprana, por lo que a la hora de comenzar el proyecto, la mayoría de grupos ya habrían sido formados, llegando al límite de integrantes. Aquellos grupos que no habían sido completados, ya habrían comenzado y adelantado parte del proyecto, motivo por el cual decidí que lo más justo sería realizar todo el trabajo por mi cuenta. Esto impactó en parte la evolución del repositorio remoto (este punto será tratado en la sección "Repositorio Git y versionado").

1. Repositorio Git y versionado

    Este proyecto, al tratarse de un trabajo realizado por solamente una persona, fue llevado a cabo en su mayoría en un repositorio local, habiendo creado a la hora de la preparación para la entrega del proyecto un repositorio remoto en GitHub de forma que todos los archivos y la totalidad del proyecto pudiera ser entregado correctamente.
    A la hora de trabajar con Git, llevé a cabo una gran cantidad de commits, con el objetivo de poder guardar de forma organizada y en el mismo lugar, todos los archivos e ideas que fueron surgiendo a lo largo del desarrollo del proyecto. 
    Cabe aclarar que dentro del repositorio solo trabajé con la rama main, sin hacer uso de ramas separadas, ya que a la hora de trabajar, siendo una sola persona encargada del proyecto y conociendo plenamente la organización del mismo, consideré que la creación de ramas separadas no sería realmente necesaria, y el trabajo sería más fácil de llevar y entender si los commits se realizaban de forma organizada en la rama main.
    Dentro del repositorio GitHub, hay una carpeta de nombre "Evolución repositorio" que contendrá información sobre todos los commits realizados y el log del mismo (información adicional sobre mi experiencia con el proyecto trabajando en Git será tratada en la sección "Reflexión").
    Link del repositorio remoto GitHub: https://github.com/LagartoBassano/Bassano.git

2. Elicitación

    A la hora de realizar entrevistas, estaba claro que sería necesario obtener un conjunto heterogéneo de opiniones y visiones de personas que pudieran desempeñarse de manera marcada y diferenciada entre ellos de usarse la aplicación que se pretende crear. De esta forma, es más fácil llegar a conclusiones que permitan identificar y desarrollar los requisitos imperativos a llevar a cabo para que todos los usuarios de la aplicación, pese a vivir la realidad de dicha aplicación de forma distinta, puedan manejarse y utilizarla con facilidad, procurando siempre brindarle al usuario la mejor experiencia posible.
  
    2.1. Caracterización de usuarios

      Con el objetivo anteriormente planteado, decidí centrarme en tres tipos de usuarios (o User Personas) que a grandes rasgos encierran todos los posibles usuarios de la aplicación, y estos son: espectador casual, espectador aficionado y espectador acérrimo.
      Sin embargo, luego de llegar a la conclusión de que estas tres categorías podrían englobar a todos los posibles usuarios de la aplicación (espectadores del mundial), comencé a verificar dicha conclusión.
      Decidí verificarlo mediante una simple pregunta que realicé a doce personas. Esta verificación consistió en escribir una descripción breve de cada una de las tres caracterizaciones y preguntarle a estas personas si se sentían identificados con alguna de las tres.
      Luego de esta verificación, llegué a la conclusión de que sería importante hilar un poco más fino, con el objetivo de poder capturar los diferentes matices que cada caracterización podría encerrar.
      Finalmente, llegué a la siguiente caracterización de usuarios:

      2.1.1 Espectador casual

            Dentro de este User Persona podemos encontrar al espectador del mundial que no tiene un interés remarcable por los partidos del mismo, interesándose tal vez en los partidos de su selección. Dentro de esta categoría podemos destacar dos tipos de espectadores casuales:

            A. Espectador casual no hincha

                Este especador no solo no está interesado en los partidos del mundial en general, sino que tampoco tiene especial interés por los partidos de su selección. Esto no significa que no quiera verlos, sino que no tiene mayor inconveniente en perderse un partido de su selección si tiene otra cosa que hacer.
                Aunque pueda parecer que este tipo de usuario no estaría especialmente interesado en usar una aplicación que detalle el fixture de los partidos del mundial, desde un principio consideré todo lo contrario, y decidí comprobarlo. De las doce personas que entrevisté, dos cayeron en esta categoría. Por lo que decidí realizarles una serie de preguntas que me permitieran definir si esta aplicación podría ser de cierto interés potencial para ellos, logrando tal vez despertar cierta afición por el mundial o al menos los partidos en los que jugara su selección, llegando a los resultados que esperaba. A pesar del pequeño tamaño de la muestra (2), ambos cuestionados afirmaron que la idea de la aplicación les resultaba interesante, y que de ser una aplicación de su agrado, se verían interesados en usarla y quizás ver algunos partidos al menos de su selección.
                Debido a este potencial interés encontrado en este tipo de usuario, considero importante tomarlo en cuenta dentro de las posibles caracterizaciones de usuario para la aplcación en desarrollo.

            B. Espectador casual hincha

                El espectador casual hincha no tiene un mayor interés por el mundial en general. Sin embargo, sí demuestra interés por los partidos de su selección y está decidido a verlos todos.
                Para poder identificar con mayor claridad a este tipo de usuario, luego de dejar establecido su interés por los partidos de su selección, realicé una serie de preguntas para comprobar la falta de interés por el resto de partidos del mundial. Preguntas entre las cuales se encuentra "¿Verías la final del mundial aunque no la juegue tu selección?", entre otras preguntas del estilo.
      
      2.1.2 Espectador aficionado

            Este User Persona demuestra gran interés por los partidos de su selección. Además, muestra cierto interés por determinados partidos del mundial que no incluyen a su selección entre las que jugarán pero de todas formas son partidos de interés.
            A la hora de identificar entre los entrevistados que personas caerían dentro de esta categoría, decidí realizar una serie de preguntas, algunas más directas entre las cuales, por ejemplo, se encuentra "¿Estás interesado en ver partidos donde no juegue tu selección?" o "¿Te interesa ver partidos de alguna otra selección en particular?", así como preguntas más indirectas relacionadas, por ejemplo, a partidos de interés general del mundial pasado, como "¿Recordás ver algún partido del mundial pasado?", u otras más específicas como "¿Recordás ver el partido de Portugal vs España de 2018?" (partido recordado por su anticipación y porque todo el mundo quería verlo).
            Cabe mencionar que dentro de esta categoría, uno de los entrevistados que formó parte de los seis entrevistados finales (se hablará de eso en la sección "Especificación") es de nacionalidad alemana, lo cual ayuda a poder conseguir un espectro más amplio de visiones de los entrevistados.
    
        2.1.3 Espectador acérrimo

            Dentro de este tipo de usuario caen los espectadores del mundial interesados en ver un gran número de partidos que no incluyan a su selección (se sobreentiende que están interesados en ver los partidos de su selección), ya sea ver ciertos partidos de interés o directamente ver todos los partidos posibles.
            Los entrevistados para los User Stories del tipo espectador acérrimo fueron los que plantearon funcionalidades de mayor exigencia y especifidad, teniendo que descartar algunas por su quasi imposibilidad o gran dificultad.

    El modelo conceptual del problema se encuentra dentro del repositorio en la carpeta "Modelo conceptual del problema"

3. Especificación

    Para la especificación, fueron seleccionados seis de los doce entrevistados iniciales. Estos seis usuarios están divididos de la siguiente forma: dos entran en el tipo espectador casual, donde uno es un espectador casual hincha y uno es no hincha, dos entran en el tipo espectador aficionado y dos entran en el tipo espectador acérrimo.
    De los seis entrevistados, cinco son uruguayos (hinchan por Uruguay) mientras que el sexto es uruguayo alemán (hincha por Alemania).
    Las especificaciones y funcionalidades fueron obtenidas a partir de la técnica o método del "Como, quiero, para", a partir del cual planteé una simple tarea a los entrevistados, intentar pensar que funcionalidades debería tener la app, que cosas les debería permitir hacer, y formalizar dichas ideas especificando que tipo de usuario son, que es lo que quieren que la app tenga o permita y para qué.
    Posteriormente, mediante análisis, prioricé las funcionalidades que consideré más importantes y reduje el número de funcionalidades finales planeadas para la aplicación.
    De esta forma, seleccionando algunos User Stories repetidas y otras no repetidas pero de gran utilidad, formalicé los requisitos funcionales y transformé las User Stories seleccionadas para desarrollar en ocho Use Cases. Las listas con los User Stories y los Use Cases se encuentran dentro de la carpeta "User Stories/Use Cases".
    Los requisitos y bocetos de IU se encuentran en el documento "Requerimientos y bocetos de IU" dentro de la carpeta "docs".

4. Validación y verificación

    La validación y verificación del proyecto fueron realizadas en dos partes.
    Para la primera parte, diseñé tres bocetos de interfaz de usuario los cuales presenté a los seis entrevistados para la especificación. De estos tres bocetos, el entrevistado podía elegir uno que le pareciera el más correcto o, si se animaba, seleccionar uno para puntualizar modificaciones que bajo su punto de vista mejorarían la interfaz. Luego de realizar dichos bocetos, pero previo a su presentación, verifiqué los requisitos de la especificación con cada uno de los bocetos.
    Para la segunda parte, diseñé otros tres bocetos que contuvieran las modificaciones e ideas propuestas por los entrevistados. Estos bocetos fueron presentados nuevamente a los entrevistados bajo la misma consigna y nuevamente, los requisitos de la especificación fueron verificados con estos bocetos.
    Finalmente, con el feedback obtenido luego de la segunda parte, diseñé un boceto final que contiene la amplia mayoría de modificaciones e ideas propuestas por los entrevistados.
    Este boceto final fue nuevamente presentado a los entrevistados para la validación, y realicé la verificación de la especificación.
    Como nota, el boceto final recibió algo de feedback negativo constructivo. Este mismo está dividido en un grupo de dos entrevistados a los que no les parecía atractivo ni necesaria la presentación de partidos en slide y otro entrevistado al que no le resultó atractiva la presentación de partidos en lista.

5. Reflexión

    Para empezar, al ser un proyecto realizado de manera individual, no hace falta dar detalles de quien realizó determinadas partes del mismo ya que todo el proyecto fue realizado por mí (Germán Bassano) de forma individual.
    Como primer aprendizaje destacable está el uso de Git. Por experiencias personales, puedo afirmar que pese a estudiar esta carrera puedo resultar un poco reacio a implementar con gran peso herramientas nuevas y desconocidas. Como ejemplo, me costó un año entero aceptar el comenzar a utilizar el VS Code como mi editor predeterminado de texto para programar. Sin embargo, con la herramienta de Git me pasó todo lo contrario, ya que aunque me encontraba reacio al principio, pude ver su gran utilidad desde el principio del proyecto, ayudándome a organizar mis archivos de forma ordenada, llevar un historial claro de modificaciones sobre el proyecto y poder acceder a herramientas que facilitan la realización del mismo.
    Por otra parte, encontré gran enrriquecimiento en el área de Ingeniería de Requisitos. Un área que hasta el momento era inexplorada por mi persona y que resultó de enorme utilidad e interés. El hecho de plantear de forma amplia requisitos mediante la obtención de información para luego realizar un proceso de análisis, especificación y posterior validación es algo a lo que una persona quizás no se le ocurra de entrada cuando piensa en Ingeniería de Software y proyectos de este área. A pesar de esto, llevando a cabo el proyecto descubrí la importancia de la Ingeniería de Requisitos y su enorme aplicabilidad, siendo esta un área en la que me interesaría adquirir bastos conocimientos.
    En cuanto a las entrevistas y obtención de información, me di cuenta de lo complicada que puede llegar a ser la comunicación entre el equipo de desarrollo y los potenciales usuarios si esta comunicación no se realiza de forma prolija y ordenada, con previa planificación.
    En varios momentos me encontré recibiendo propuestas de User Stories inaplicables o de una dificultad totalmente desconocida para los usuarios. En otros momentos, vi como dos entrevistados tenían visiones totalmente distintas de lo que haría atractiva o no atractiva a la aplicación, teniendo que llegar a un punto medio entre ambas.
    Por todo esto, para futuros proyectos, podría hacer uso de técnicas diferentes en las que he estado pensando, como, por ejemplo, presentar bocetos codiseñados con algún usuario a otros usuarios para obtener opiniones e ir mezclando conceptos e ideas para llegar de forma más natural al boceto final.



      

       