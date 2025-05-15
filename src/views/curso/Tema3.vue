<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Características'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-4 Según Castro (2015), el Glosario de la Reforma Educativa, señala que no existe un único ambiente óptimo de aprendizaje, sino una variedad infinita que enriquece la enseñanza, lo que ha llevado a numerosas investigaciones para mejorar estos entornos. Algunas investigaciones se centran en identificar características comunes que permiten maximizar el aprovechamiento de los ambientes educativos, aunque no siempre es posible seguir un único patrón. A continuación, se presentan las principales características que deben tener los ambientes de aprendizaje, según la revisión de estudios de diversos autores.

    .bg-full-width.bg-color-4.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Principales características de los ambientes de aprendizaje 
            p.mb-4(data-aos="fade-right") Se estudia en el PDF <b>Principales características de los ambientes de aprendizaje</b>, cómo estos espacios van más allá de su configuración física, convirtiéndose en entornos dinámicos que fomentan el aprendizaje activo, la creatividad y la interacción social. A través de un enfoque integral, se analizan los factores que influyen en su diseño, sostenibilidad y flexibilidad, así como el impacto que tienen en el desarrollo de habilidades cognitivas, emocionales y sociales de los estudiantes. Además, se exploran estrategias para la optimización de estos ambientes, garantizando que respondan a las necesidades educativas actuales y futuras.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Principales características de los ambientes de aprendizaje .
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/1.png', alt='')



    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://dialnet.unirioja.es/descarga/articulo/7911725.pdf" target="_blank" rel="noopener noreferrer") Álvarez, G. Y. C., & Correa, I. D. A. (2021). Características didácticas de un ambiente de aprendizaje colaborativo para la resolución de problemas con tecnología en la educación media. Plumilla Educativa, 27(1), 15-38. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.lifeder.com/ambientes-aprendizaje/" target="_blank" rel="noopener noreferrer") Ayala, M. (18 de enero, 2021). Ambientes de aprendizaje. Lifeder. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=c_YJ6dF4NyM " target="_blank" rel="noopener noreferrer") Vera, F. A. [@fredyarmandoveratoledo5874]. (2023, 31 de octubre). Ambiente adecuado para el aprendizaje. Youtube. 



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
export default {
  name: 'Tema3',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
