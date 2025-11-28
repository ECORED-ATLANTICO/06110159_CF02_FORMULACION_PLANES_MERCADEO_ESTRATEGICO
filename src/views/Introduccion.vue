<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center.align-items-center.mb-5
      .col-8.col-lg-3.mb-lg-0.mb-3(data-aos="fade-left")
        figure
          img(src="@/assets/curso/introduccion/img_1.png", class="img-fluid")
      .col-12.col-lg-9
        p.mb-3(data-aos="fade-left") El componente formativo Plan de mercadeo, ofrece al aprendiz herramientas técnicas y prácticas para abordar la formulación de estrategias comerciales basadas en análisis del mercado potencial, alineadas con los objetivos y metodologías de planeación estratégica. A partir del conocimiento de los objetivos organizacionales, la programación de recursos y los criterios de optimización, se fortalecen las capacidades para estructurar actividades coherentes que orienten el logro de resultados en mercados competitivos.  
        .row.justify-content-center.align-items-center.mb-5.tarjeta.color-primario-20.p-4.rounded-3.mb-0
          .col-5.col-lg-2.mb-lg-0.mb-3(data-aos="fade-left")
            figure
              img(src="@/assets/curso/introduccion/img_2.png", class="img-fluid d-none d-lg-block mb-0")
          .col-12.col-lg-10
            p.mb-3(data-aos="fade-left") Este componente también enfatiza en la aplicación de metodologías estratégicas, el uso de herramientas de análisis y la evaluación mediante indicadores, con un enfoque en la toma de decisiones informada y la mejora continua. Además, promueve el desarrollo de pensamiento crítico y la gestión eficiente de recursos para garantizar la efectividad del plan. Así, se contribuye a la formación de profesionales capaces de diseñar planes de mercadeo integrales y sostenibles.  

    
    figure.mb-5
      .video.mb-2
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Upcvs8smTzI?si=2U47IJ3jTRFSr8kR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Plan de mercadeo

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
