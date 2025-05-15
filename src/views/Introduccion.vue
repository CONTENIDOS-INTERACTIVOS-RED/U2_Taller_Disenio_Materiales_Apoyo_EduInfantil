<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/intro/1.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") Bienvenidos a la unidad 2, Ambientes de aprendizaje. La presente unidad se centra en la importancia y el diseño de los ambientes de aprendizaje, fundamentales para facilitar un proceso educativo efectivo y significativo. Esta unidad abordará los diversos aspectos que contribuyen a la creación de un entorno propicio para el aprendizaje, destacando su relevancia en el contexto del curso.
    
        .bg-color-1.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Al finalizar esta unidad, se espera que los estudiantes sean capaces de diseñar materiales educativos apropiados y útiles en una secuencia didáctica, identificando grados de dificultad y utilizando de manera creativa, diferentes recursos. Además, se busca que los estudiantes generen e implementen aprendizajes significativos en el aula, adaptándose a las necesidades y características de sus alumnos.
    
    p.mb-4 La estructura de esta unidad incluye una descripción general de los temas que se abordarán, tales como concepto, antecedentes, características, principios y estructura. También se realizarán actividades prácticas y colaborativas que fomenten la participación activa y el intercambio de ideas entre los estudiantes.

    .bg-full-width.bg-h85
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-2
                h5.mb-5 Se invita a aprovechar al máximo esta unidad.
                p Se invita a los estudiantes a explorar, participar y colaborar en esta unidad, con el objetivo de enriquecer su experiencia educativa y desarrollar habilidades esenciales para su formación académica y profesional.

              .col-lg-4(data-aos="zoom-in").order-1.mb-3.mb-lg-0
                img.img-fluid(src='@/assets/curso/intro/3.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

</template>
