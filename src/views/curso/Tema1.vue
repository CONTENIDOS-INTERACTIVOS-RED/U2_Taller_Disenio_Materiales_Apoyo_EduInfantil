<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Concepto de ambientes de aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-4 Durante esta segunda unidad, estaremos abordando el tema de los ambientes de aprendizaje, veremos su concepto, antecedentes, características, principios y estructura. Para iniciar preguntémonos:

    .row.justify-content-center.align-items-stretch.mb-4
      .col-lg-6
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-0 ¿Qué diferencias se observan entre un aula tradicional y un entorno de aprendizaje digital?

      .col-lg-6
        .bg-color-3.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-0 ¿Pueden dar ejemplos de situaciones en las que un ambiente de aprendizaje específico haya impactado positivamente en su aprendizaje?
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/2.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Para Rubio (2021), los ambientes de aprendizaje son entornos diseñados específicamente para facilitar el proceso de enseñanza-aprendizaje. Aunque en un sentido amplio, incluyen cualquier escenario donde se enseñe, su significado se centra en aquellos espacios construidos intencionadamente para fomentar una interacción efectiva entre estudiantes y docentes. Estos ambientes se organizan cuidadosamente para optimizar el uso de recursos didácticos y el tiempo creando, de esta manera, situaciones de aprendizaje que favorecen la colaboración y el intercambio de ideas.
    
        .bg-color-2.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 En años recientes, la planificación de estos ambientes ha adquirido mayor relevancia, impulsada por nuevas teorías pedagógicas que abogan por la participación activa de los estudiantes y el compromiso de los educadores. 
        p Al establecer un ambiente de aprendizaje propicio, se asegura que los contenidos sean asimilados eficientemente, promoviendo un aprendizaje significativo y cómodo para todos los involucrados.
    
    .bg-full-width.bg-h85-2.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                p En este sentido Duque Romero, et al. (2023), sostiene que, en la educación inicial, los ambientes de aprendizaje son fundamentales, dado que son los espacios físicos y psicosociales donde niños y adultos interactúan con un propósito educativo. 
                p Según Arias et al. (2005), citado por los autores mencionados, estos ambientes organizados estratégicamente por los maestros, buscan favorecer el aprendizaje a través de procesos cognitivos y afectivos, promoviendo el desarrollo de competencias.

              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema1/4.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-4 Por ejemplo, un aula con rincones de juego temáticos (como una "tienda" o un "hospital") permite a los niños explorar diferentes roles y situaciones, fomentando tanto su desarrollo cognitivo como social. 

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/5.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-3.p-4.mb-5(data-aos="fade-left")
          p.mb-0 Desde esta perspectiva, los maestros juegan un papel esencial en la construcción de vínculos y en la atención a la diversidad, influyendo significativamente en el desarrollo infantil (Salinas-Quiroz, 2017; Salinas-Quiroz et al. 2015), citados por Duque Romero, et al. (2023), las interacciones entre adultos, niños y materiales educativos, involucran procesos cognitivos y socioafectivos, trascendiendo la mera organización del aula, como señalan Johnson y Johnson (citados en Arias et al. 2005). Por ejemplo, un maestro que guía a los niños en la construcción de un mural colaborativo, no solo les enseña sobre colores y formas, sino que también fomenta la cooperación y el respeto mutuo.
        p(data-aos="fade-left") Así mismo, para Fuentes (2022), los ambientes de aprendizaje son espacios diseñados para facilitar la adquisición de conocimientos y el desarrollo de competencias, guiados por un docente o formador. Estos entornos ayudan a mitigar las dificultades de aprendizaje más comunes en el aula. Para ser efectivos, deben incluir elementos sociales, culturales, humanos y logísticos, que son esenciales en el proceso de enseñanza-aprendizaje.
    
    .bg-color-4.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema1/6.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") Un ambiente de aprendizaje debe adaptarse a las necesidades y características del grupo de estudiantes, estableciendo una base sólida para una instrucción adecuada. Su principal reto es integrar todos los componentes necesarios para crear un sistema efectivo que promueva el aprendizaje autónomo e independiente, donde los estudiantes se responsabilizan de su propio proceso de aprendizaje.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/7.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Además, estos ambientes deben facilitar la interacción y el trabajo en equipo, enriqueciendo el aprendizaje a través de la colaboración. Un buen ambiente de aprendizaje también debe apoyar las estrategias y estilos de enseñanza propuestos por el docente, garantizando que todos los estudiantes puedan participar y contribuir al conocimiento colectivo (Fuentes, 2022).
    
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/8.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Los ambientes de aprendizaje son escenarios diseñados intencionadamente para facilitar la adquisición de conocimientos, permitiendo a los estudiantes generar un nuevo aprendizaje a través de sus habilidades y herramientas (Guevara, 2024). Este entorno incluye factores como la iluminación, el mobiliario, los materiales, así como la motivación, el interés, la comunicación y las interacciones entre las personas, todos esenciales para el desarrollo integral de las aptitudes de los alumnos.
    
    .bg-full-width.bg-h85-2.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                p Por su parte, Duarte (2003), sustenta que, el ambiente se entiende como una construcción diaria que asegura la diversidad y enriquece la vida en relación con los seres humanos. El concepto de ambiente educativo se refiere a un sujeto que actúa y transforma al ser humano, implicando que diversas entidades como la ciudad, la escuela, la familia, y el barrio, desempeñan un rol educativo. Reflexionar sobre estos ambientes destinados al sano desarrollo de las personas, implica verlos como un tejido colectivo que promueve el aprendizaje y la educación.

              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema1/9.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/10.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Además, el ambiente educativo se define como el escenario en el que se desarrollan condiciones favorables para el aprendizaje, un espacio y tiempo en movimiento donde los participantes adquieren capacidades, competencias y valores. Para crear estos ambientes, se consideran dos componentes esenciales: los desafíos y las identidades. Los desafíos son retos significativos que se generan desde las iniciativas propias o propuestas por educadores, fomentando la autonomía y el desarrollo de valores en el grupo (Duarte, 2003).
    
        .bg-color-3.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La identidad también juega un papel crucial en los ambientes educativos, puesto que la gestión de las identidades culturales permite establecer relaciones de solidaridad y apoyo mutuo. Así, el ambiente educativo no se limita a las condiciones materiales necesarias para implementar un currículo, sino que se basa en las dinámicas del proceso educativo que involucran experiencias y relaciones interpersonales (Duarte, 2003).
        p Por último, la comprensión de los ambientes educativos se ha ampliado, porque no solo se considera el espacio físico, sino también las interacciones que ocurren en él. Esto incluye la organización del espacio, las relaciones entre sus elementos y las pautas de comportamiento que se desarrollan. En este contexto, se analizan los roles, criterios y actividades que se llevan a cabo, reconociendo la complejidad de las interacciones humanas.
        

    #t_1_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.1] Tipos de ambientes de aprendizaje
    
    p.mb-4 Los ambientes de aprendizaje son diversos y están influenciados por múltiples factores que se pueden clasificar en varias categorías:

    .row.align-items-start.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema1/12.png", alt="").mb-4.mb-lg-0
      .col-lg-8.mb-3.mb-lg-0.order-1
    
        AcordionA(tipo="b")
          .div(titulo="Ambientes físicos")
            p Según fuentes (2022), una de estas categorías son los ambientes físicos, que se refieren a todo lo que rodea a los estudiantes, incluyendo los materiales y contenidos del aula. Los maestros tienen la responsabilidad de adaptar los recursos disponibles al modelo de aprendizaje que se esté utilizando, asegurando así un entorno propicio para el desarrollo educativo. 
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-9
                p.mb-0 <b>Ejemplo.</b> Un aula de clase en una escuela secundaria, donde los estudiantes tienen acceso a pizarras interactivas, materiales didácticos y recursos impresos. Los maestros pueden reorganizar el espacio según las actividades del día, como trabajar en grupos o realizar experimentos científicos.

    
          .div(titulo="Ambientes virtuales")
            p Los ambientes virtuales son otra categoría importante, que abarcan los espacios digitales que apoyan la educación a distancia. Estos ambientes permiten identificar las características de los estudiantes que aprenden de manera remota. Es fundamental que los materiales diseñados para estos espacios sean dinámicos e interactivos, facilitando así el estudio autónomo e independiente de los alumnos (Fuentes, 2022).
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-9
                p <b>Ejemplo.</b> Una plataforma de e-learning como Moodle, donde los estudiantes pueden acceder a materiales de clase, participar en foros de discusión, realizar tareas y recibir retroalimentación de sus docentes en línea. Los cursos están diseñados para ser interactivos y adaptativos a las necesidades individuales de los estudiantes.
    
    p.mb-4 Dentro de los ambientes virtuales, encontramos las <b>plataformas de e-learning</b>. Estas plataformas, como Moodle y Blackboard, son entornos virtuales que permiten la gestión de cursos en línea. Facilitan la distribución de materiales, la realización de actividades y la interacción entre estudiantes y docentes, a través de:

    .bg-full-width.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-lg-2
    
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/14.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Blogs educativos
                p.text-center Los blogs son herramientas que permiten a los docentes y estudiantes compartir información, reflexiones y recursos educativos. Fomentan la participación activa y el intercambio de ideas (Coppola, 2022).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/15.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Wikis
                p.text-center Las wikis son plataformas colaborativas donde los estudiantes pueden crear y editar contenido de manera conjunta. Son útiles para proyectos grupales y la construcción de conocimiento colectivo (Coppola, 2022).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/16.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Redes sociales
                p.text-center Las redes sociales, como Facebook y Twitter, pueden ser utilizadas como herramientas educativas para fomentar la comunicación y el intercambio de información entre estudiantes y docentes (Coppola, 2022).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/17.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Entornos Virtuales de Aprendizaje (EVA)
                p.text-center Estos entornos, como Google Classroom y Khan Academy, proporcionan un espacio en línea donde los estudiantes pueden acceder a recursos educativos, realizar actividades y recibir retroalimentación (Coppola, 2022).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/18.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Simuladores y juegos educativos
                p.text-center Los simuladores y juegos educativos son herramientas interactivas que permiten a los estudiantes aprender a través de la práctica y la experimentación, en un entorno virtual (Coppola, 2022).
    
          .col-lg-4.order-lg-1
            figure
              img(src='@/assets/curso/tema1/13.png', alt='')

        p Prosiguiendo, tenemos:
    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/19.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Ambientes informales
              p Abarcan los espacios de aprendizaje que ocurren fuera del contexto escolar, donde no existen planes de estudio ni acreditaciones formales. Aunque carecen de un marco estructurado, estos ambientes también están regidos por normas y reglas de comportamiento, donde cada miembro desempeña un rol específico en el proceso de aprendizaje. 
              p <b>Ejemplo.</b> Un club de robótica comunitario donde niños y adolescentes se reúnen para aprender sobre robótica y programación. No hay un plan de estudios formal, pero los participantes colaboran en proyectos, comparten conocimientos y se adhieren a reglas de comportamiento, establecidas por el grupo (Fuentes, 2022).

    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/20.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Ambientes formales
              p Estos se refieren a las instituciones educativas, tanto públicas como privadas, que operan bajo regulaciones específicas en cada país. Estos ambientes están estructurados en diferentes niveles educativos, como primaria, secundaria y educación superior, cada uno con su respectiva acreditación que garantiza la calidad de la educación impartida. La institucionalidad y la jerarquía, son características claves de estos ambientes.
              p <b>Ejemplo.</b> Una universidad pública que ofrece programas acreditados de grado y posgrado. Los estudiantes asisten a clases regulares, participan en actividades extracurriculares y deben cumplir con los requisitos académicos establecidos por la institución, para obtener sus títulos (Fuentes, 2022).


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dominiodelasciencias.com/ojs/index.php/es/article/view/3272/7489" target="_blank" rel="noopener noreferrer") Campoverde, M. M. P., Mendoza, M. C. B., Delgado, V. M. Z., & Pazmiño, R. E. V. (2023). Ambientes de aprendizaje con material reciclable para desarrollar la motricidad fina en preescolares. Dominio de las Ciencias, 9(2), 102-125.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.vocaeditorial.com/blog/entornos-virtuales-de-aprendizaje/?" target="_blank" rel="noopener noreferrer") Txt, /blog/humans. (19 de febrero, 2022). Los 10 Entornos Virtuales de Aprendizaje más útiles -. Voca Editorial. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=P6scoxSUjQs" target="_blank" rel="noopener noreferrer") Pascualbravovirtual. ( 2021, 7 de octubr). Los ambientes de aprendizaje. Youtube.  

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
