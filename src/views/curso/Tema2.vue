<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Antecedentes de los ambientes de aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-4 Para conocer sobre esta temática, lo invitamos a ver el siguiente video.

    .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/8ldDjJx6ebQ?si=csexyntpklFFzZvb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/1.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 La evolución de los ambientes de aprendizaje, ha sido influenciada por varios hitos a lo largo de la historia. Siguiendo el recorrido histórico realizado por la licenciada María Angélica Alarcón (s/f), describiremos algunos de los momentos más significativos que han marcado esta evolución.
    
    .row.align-items-start.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/1.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
    
        AcordionA(tipo="b")
          .div(titulo="Aulas tradicionales Parte 1")
            p Durante siglos, la educación formal se centró en aulas con maestros impartiendo lecciones directamente a los estudiantes. Este modelo ha sido la base de la educación desde la antigüedad, hasta la era moderna. Las aulas tradicionales se caracterizan por la enseñanza directa y la interacción cara a cara entre maestros y estudiantes. Desde aproximadamente el 28 a. C. hasta el año 2000, la enseñanza se basaba predominantemente en un modelo conductista. Este modelo, influenciado por psicólogos como B.F. Skinner y Ivan Pavlov, se centraba en la idea de que el aprendizaje humano podía ser observado y medido a través de cambios en el comportamiento. Según este enfoque, el docente era el principal actor en el proceso de enseñanza-aprendizaje, desempeñando un papel central en la transmisión de conocimientos y controlando el entorno educativo.
    
          .div(titulo="Aulas tradicionales Parte 2")
            p En este contexto, el docente era la figura de autoridad y el principal transmisor de la información. La enseñanza se realizaba mediante la presentación de contenidos y la realización de ejercicios repetitivos. No existían recursos didácticos avanzados como los que conocemos hoy en día, lo que limitaba la diversidad de métodos de enseñanza. El trabajo individual era la norma, y los estudiantes rara vez colaboraban entre sí en actividades de aprendizaje (Alarcón, s/f).
            p La Edad Antigua, es un período histórico que se caracteriza por el desarrollo de la escritura, una de las innovaciones más significativas de la humanidad. La invención de la escritura permitió la transmisión y conservación de conocimientos, mensajes e información a lo largo del tiempo y el espacio.

    
          .div(titulo="Aprendizaje por correspondencia")
            p Con la escritura, surgió la posibilidad de la comunicación asincrónica, es decir, la capacidad de enviar y recibir mensajes sin necesidad de la presencia simultánea del emisor y el receptor. Las cartas se convirtieron en un medio esencial para el intercambio de información. Esta forma de comunicación facilitó el aprendizaje y la difusión de conocimientos, permitiendo a las personas compartir ideas, instrucciones y relatos, a largas distancias.
            p Uno de los primeros ejemplos de aprendizaje a distancia, puede encontrarse en el uso de cartas para enseñar y aprender. Los filósofos y maestros de la antigüedad, como Aristóteles, utilizaban la correspondencia para comunicarse con sus discípulos y transmitirles enseñanzas. Esta modalidad permitió que el conocimiento llegara a personas que no podían estar físicamente presentes en los centros de aprendizaje. 
            p El aprendizaje por correspondencia en la Edad Antigua, es un precursor de los modernos ambientes de aprendizaje a distancia. Aunque rudimentarios en comparación con las tecnologías actuales, estos primeros esfuerzos demostraron el potencial de la educación fuera del aula física. La escritura permitió que los conocimientos se documentaran y se transmitieran a través de generaciones, creando una base para el desarrollo de sistemas educativos más complejos (Alarcón, s/f).

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/2.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="Falta de aprendizaje colaborativo Parte 1")
            p Durante el período comprendido entre 1801 y 1900, el enfoque educativo se centró en atender a minorías con necesidades específicas. Este modelo, influenciado por el conductismo, se caracterizaba por un enfoque en el control y la modificación del comportamiento observable. Los estudiantes adoptaban un papel pasivo en el proceso de enseñanza-aprendizaje, siendo receptores de información, más que participantes activos. Este modelo carecía de comunicación bidireccional, lo que significa que no había un intercambio activo de ideas y conocimientos entre el docente y los estudiantes. El docente dictaba el contenido, y los estudiantes simplemente lo recibían sin tener la oportunidad de expresar sus opiniones, dudas, o contribuir de manera significativa al proceso de aprendizaje (portal LaHistoria, 2024).
          .div(titulo="Falta de aprendizaje colaborativo Parte 2")
            p La educación durante este período, no fomentaba el aprendizaje colaborativo. Los estudiantes trabajaban de manera individual, completando tareas y ejercicios de manera solitaria. Este enfoque limita el desarrollo de habilidades sociales y de trabajo en equipo, debido a que no había oportunidades para la colaboración y la interacción entre compañeros.
            p Aunque el enfoque principal era la enseñanza individualizada y pasiva, algunas iniciativas comenzaron a centrarse en atender a minorías con necesidades educativas especiales. Sin embargo, estos esfuerzos eran limitados y no estaban ampliamente implementados en los sistemas educativos.
    
          .div(titulo="Mayor interacción y medios de comunicación")
            p Entre aproximadamente 1901 y 1970, los ambientes de aprendizaje experimentaron una notable evolución, marcada por varios cambios en la interacción entre docentes y alumnos, así como en las metodologías y herramientas utilizadas. Durante este período, la comunicación entre docentes y alumnos se vio facilitada por la disponibilidad de medios como el correo y el teléfono. Estas herramientas permitieron una comunicación más frecuente y efectiva, lo que contribuyó a fortalecer la relación educativa y a personalizar el apoyo a los estudiantes. El uso del correo permitió a los estudiantes enviar sus trabajos y recibir retroalimentación de sus tutores, mientras que el teléfono facilitó consultas rápidas y la resolución de dudas (Alarcón, s/f).
            p El papel de los tutores se volvió más prominente, ofreciendo un apoyo más personalizado y constante a los estudiantes. Este enfoque promueve la autoevaluación, donde los estudiantes se involucraron de manera activa en la valoración de su propio progreso y desempeño. La autoevaluación fomenta una mayor responsabilidad y autonomía en el proceso de aprendizaje, permitiendo a los estudiantes identificar sus fortalezas y áreas de mejora.

    .bg-full-width.bg-h85.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                p.mb-0 Durante este período (1901 y 1970), el modelo cognitivista comenzó a ganar relevancia. Este enfoque, influenciado por psicólogos como Jean Piaget y Lev Vygotsky, se centró en comprender los procesos mentales que subyacen al aprendizaje. El cognitivismo enfatizaba la importancia de la percepción, la memoria y el pensamiento crítico, en la adquisición de conocimientos. Este modelo promovía un aprendizaje más activo y participativo, en contraste con el enfoque conductista pasivo anterior (portal LaHistoria, 2024).

              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/3.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    TabsC.color-primario.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Aulas presenciales" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Aulas presenciales
            p Las aulas seguían siendo el entorno principal de aprendizaje, pero con una mayor interacción y participación activa de los estudiantes. Los docentes comenzaron a implementar métodos más dinámicos, como discusiones en grupo y actividades prácticas.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/4.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Cursos por correspondencia" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Cursos por correspondencia
            p La educación a distancia, a través de cursos por correspondencia, se hizo más común, permitiendo a los estudiantes que no podían asistir físicamente a las clases, continuar su educación.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/5.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Tutorías personalizadas" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Tutorías personalizadas
            p Los tutores desempeñan un papel clave en el apoyo individualizado a los estudiantes, brindando orientación y retroalimentación constante.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/6.png', alt='', style="width: 100%;")
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Telefonía educativa" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Telefonía educativa
            p El teléfono se utilizó como una herramienta para consultas rápidas y apoyo educativo, facilitando la comunicación directa entre estudiantes y docentes (portal LaHistoria, 2024).
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/7.png', alt='', style="width: 100%;")
    
    p.mb-4 Continuemos el recorrido con:

    h2.mb-5(data-aos="fade-left") Educación de la tecnología digital (ambiente a distancia)
    
    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/8.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") Entre aproximadamente 1979 y 1989, se inició un cambio significativo en la educación con la interacción directa entre docentes y alumnos, lo que favoreció una comunicación bidireccional. Este periodo marcó una transición importante en el rol del docente, evolucionando de ser un transmisor de conocimientos a un orientador, facilitador y estimulador del aprendizaje. El docente empezó a guiar a los estudiantes en el proceso educativo, fomentando una mayor participación activa (Alarcón, s/f).
        p Se incorporaron nuevas tecnologías y recursos interactivos que transformaron la dinámica de enseñanza y aprendizaje. Estos recursos incluyen:

    .row.justify-content-center.align-items-stretch.mb-4
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-0 Videos educativos
              p Herramientas visuales que facilitaron la comprensión de conceptos complejos.

      .col-lg-6.mb-3.mb-lg-0
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/10.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-0 Textos digitales
              p Materiales de lectura accesibles en formato electrónico, ampliando el acceso a la información.
    
    .bg-color-8.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema2/11.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") Estos avances permitieron que el estudiante se volviera un participante activo en el proceso de enseñanza-aprendizaje, promoviendo una mayor autonomía y responsabilidad en su propio aprendizaje. Además, se implementaron diversos métodos de evaluación para valorar el desempeño de los estudiantes, de manera más integral. Este periodo fue crucial para sentar las bases de una educación más interactiva, inclusiva y centrada en el estudiante (portal LaHistoria, 2024).
      
    h2.mb-5(data-aos="fade-left") Educación en línea (ambiente a distancia)
      
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/12.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") Desde aproximadamente 1990 hasta 2018, se produjo una transformación significativa en el ámbito educativo. Durante este periodo, el alumno comenzó a asumir un rol más autodidacta, aprovechando las vastas posibilidades que ofrecía Internet para acceder a una gran cantidad de información y recursos educativos. Esto permitió a los estudiantes desarrollar habilidades de autoaprendizaje y gestión del conocimiento, adaptándose a sus propios ritmos y estilos de aprendizaje (Alarcón, s/f).
    
        .bg-color-2.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/13.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Simultáneamente, el docente experimentó una evolución en su rol, adoptando una función más como guía y facilitador del aprendizaje. En lugar de ser el único transmisor del conocimiento, el docente empezó a utilizar contenido enriquecido por Internet, lo que incluía recursos multimedia, plataformas de aprendizaje en línea, bibliotecas digitales y herramientas interactivas. Esta integración de las Tecnologías de la Información y la Comunicación (TIC) promovió un mayor uso de estas tecnologías en el aula, transformando la enseñanza tradicional (Alarcón, s/f).
        p Este periodo se caracterizó por:  

    .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/15.png")
            .col-lg-7
              h5 Interactividad
              p Los recursos digitales y las plataformas en línea, permitieron una mayor interactividad entre docentes y alumnos. Las aulas virtuales, los foros de discusión y las videoconferencias, se convirtieron en herramientas comunes, facilitando la comunicación bidireccional y el intercambio de ideas.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/16.png")
            .col-lg-7
              h5 Conectividad
              p La expansión de Internet y las redes sociales, generaron una mayor conectividad entre estudiantes y profesores de diferentes partes del mundo, fomentando el aprendizaje colaborativo y el intercambio cultural.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/14.png")
            .col-lg-7
              h5 Aprendizaje social y colaborativo
              p Se promovieron metodologías que incentivaran el trabajo en equipo, la colaboración y el aprendizaje entre pares. Las TIC permitieron que los estudiantes trabajaran juntos en proyectos y actividades, incluso a distancia.
    
    .bg-full-width.bg-color-4.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/17.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Además, se puso un énfasis significativo en incentivar la reflexión, el debate y la argumentación. Los estudiantes fueron alentados a desarrollar habilidades críticas y analíticas, participando en debates, discusiones y reflexiones sobre diversos temas.

    h2.mb-5(data-aos="fade-left") Entre 2000 y 2010, integración de las TIC en la educación

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/18.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") Durante este periodo, los ambientes de aprendizaje se transformaron significativamente gracias a la integración de las TIC. Algunas características claves de estos ambientes, fueron las aulas equipadas con tecnología. Las aulas comenzaron a contar con computadoras, proyectores, pizarras digitales interactivas y acceso a Internet, lo que permitió una mayor interactividad y acceso a recursos educativos en línea (Alarcón, s/f).
        p Conozcamos algunos de estos elementos:
    
    TabsC.color-primario.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Bibliotecas digitales" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Bibliotecas digitales
            p Se empezaron a utilizar bibliotecas digitales que ofrecían acceso a una amplia variedad de libros, artículos académicos y otros recursos educativos, permitiendo a los estudiantes realizar investigaciones más profundas y acceder a materiales actualizados.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/19.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Plataformas de gestión del aprendizaje (LMS)" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Plataformas de gestión del aprendizaje (LMS)
            p Herramientas como Moodle y Blackboard, se implementaron para gestionar cursos, asignaciones y evaluaciones. Estas plataformas ofrecían un entorno estructurado donde los estudiantes podían acceder a materiales del curso, participar en foros de discusión y recibir retroalimentación.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/20.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Laboratorios de informática" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Laboratorios de informática
            p Las instituciones educativas comenzaron a incluir laboratorios de informática donde los estudiantes podían aprender y practicar habilidades tecnológicas, programar y utilizar <em>software</em> educativo.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/21.png', alt='', style="width: 100%;")
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Ambientes colaborativos" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Ambientes colaborativos
            p Se promovió el trabajo en equipo y la colaboración a través de proyectos y actividades grupales, aprovechando herramientas digitales que facilitaban la comunicación y la coordinación entre los estudiantes.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/22.png', alt='', style="width: 100%;")
    
    h2(data-aos="fade-left") Entre 2010 y 2018, protagonismo del estudiante y modelo constructivista
    p En este periodo, los ambientes de aprendizaje continuaron evolucionando con un enfoque más centrado en el estudiante y el uso de un modelo constructivista. 
    p.mb-5 Algunas características destacadas incluyen:

    .bg-full-width.bg-color-info
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema2/23.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="2.5%" y="47.5%" numero="+")
                h5 Ambientes flexibles y dinámicos
                p Las aulas se rediseñaron para ser más flexibles, con espacios que fomentaban el trabajo en grupo y la colaboración. Los estudiantes podían reorganizar el mobiliario para adaptarlo a diferentes actividades y proyectos.
    
              .bg-color-white.box-shadow.p-3(x="19%" y="85%" numero="+")
                h5 Aulas virtuales
                p Además de las aulas físicas, se crearon aulas virtuales a través de plataformas en línea donde los estudiantes podían acceder a materiales del curso, participar en discusiones y colaborar en proyectos, sin importar su ubicación geográfica (Alarcón, s.f.).
    
              .bg-color-white.box-shadow.p-3(x="63.5%" y="95.5%" numero="+")
                h5 Recursos multimedia
                p Los docentes utilizaron una variedad de recursos multimedia, incluyendo vídeos, audios, simulaciones y juegos educativos, para enriquecer la experiencia de aprendizaje y hacerla más interactiva y atractiva.
    
              .bg-color-white.box-shadow.p-3(x="86.5%" y="86%" numero="+")
                h5 Aprendizaje basado en proyectos
                p Se implementaron metodologías como el aprendizaje basado en proyectos, donde los estudiantes trabajaban en proyectos reales y aplicaban sus conocimientos para resolver problemas, desarrollando habilidades prácticas y críticas.
    
              .bg-color-white.box-shadow.p-3(x="97.5%" y="53%" numero="+")
                h5 Evaluación integral y continua
                p Se aplicaron métodos de evaluación más variados y continuos, incluyendo la autoevaluación, coevaluación y heteroevaluación. Los estudiantes participaron activamente en la evaluación de su propio aprendizaje y el de sus compañeros.
    
    .bg-full-width.bg-color-9
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/24.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0.text-white Como podemos ver, el paso que la educación y las maneras de enseñar, fueron evolucionando, así mismo los ambientes de aprendizaje, dado que, al cambiar los roles, los espacios y los recursos, estos se han ido transformando para ser más acorde a las necesidades de cada época, si bien es cierto aún hay una brecha grande entre lo tradicional y lo actual, se pueden evidenciar grandes progresos.






    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/48353" target="_blank" rel="noopener noreferrer") Ossenbach Sauter, G. Tiana Ferrer, A. & Sanz Fernández, F. (2014). Historia de la educación: edad contemporánea: ( ed.). UNED - Universidad Nacional de Educación a Distancia. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.sutori.com/en/story/evolucion-de-los-ambientes-de-aprendizaje--amM6vVGXQWo8H42WqRicyLKb" target="_blank" rel="noopener noreferrer") Alarcón, M.A. (s/f). Evolución de los Ambientes de Aprendizaje Sutori.com. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=Ar6i2jQSkn8 " target="_blank" rel="noopener noreferrer") Mosquea, J. A. [@josea.mosquea8653]. (2020, 29 de abril). Historia y Evolución de la Educación a Distancia. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
