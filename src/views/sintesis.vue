<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .row.justify-content-center.align-items-center.mb-3
      .col-12.col-lg-12.mb-lg-0.mb-3(data-aos="fade-left")
        p.mb-0 El componente formativo Plan de mercadeo permite comprender los elementos que intervienen en la planificación estratégica comercial, desde su definición conceptual hasta su aplicación operativa en los procesos de marketing. Se inicia con el estudio de los objetivos estratégicos, abordando sus tipos, la misión, la visión y los objetivos organizacionales, así como su papel para orientar las acciones del plan. Posteriormente, se profundiza en las metodologías estratégicas, lo que permite establecer su importancia en el análisis, estructuración y selección de herramientas para la toma de decisiones en marketing.
    .row.justify-content-center.align-items-center.mb-5
      .col-8.col-lg-3.mb-lg-0.mb-3(data-aos="fade-left")
        figure
          img(src="@/assets/curso/sintesis/img_1.png", class="img-fluid d-none d-lg-block mb-0")
      .col-12.col-lg-9
        p.mb-0(data-aos="fade-left") Asimismo, se analizan los aspectos relacionados con la programación de recursos, proporcionando criterios para clasificarlos, gestionarlos adecuadamente y organizar su secuencia dentro de las actividades del plan. Se presentan los criterios de optimización que influyen en el desempeño, así como los enfoques de eficiencia, eficacia, costo-beneficio y priorización, necesarios para asignar recursos y definir acciones con base en resultados esperados. La documentación aborda el uso de indicadores como instrumentos de medición para evaluar el avance y el cumplimiento de los objetivos del plan. Para fortalecer la aplicación de estos conceptos, se detallan los aspectos fundamentales de la mejora continua y sus mecanismos de evaluación, permitiendo realizar ajustes sostenidos y mantener la pertinencia del plan frente a cambios del entorno. Finalmente, se analiza la importancia de los indicadores y procesos de evaluación como base para retroalimentar las estrategias y garantizar la evolución permanente del plan de mercadeo.
    
    .row.justify-content-center
      .col-lg-12.mb-5.bgs.p-2.brad
        figure
          img(src="@/assets/curso/sintesis/sintesis.svg", alt="El componente formativo plan de mercadeo ofrece una aproximación integral a los conocimientos fundamentales sobre la planeación estratégica comercial y la gestión estructurada de acciones de marketing. Este módulo analiza detalladamente los objetivos estratégicos, resaltando su función orientadora en cuanto a la misión, visión y metas organizacionales, y se desglosan sus tipos y alcances dentro del proceso de planificación. Asimismo, se estudian las metodologías estratégicas que permiten seleccionar enfoques y herramientas para la toma de decisiones informadas. La propuesta profundiza en la programación de recursos, así como en la clasificación, uso y secuenciación de actividades necesarias para ejecutar un plan de manera ordenada y eficiente. Además, se destacan los criterios de optimización y los indicadores de medición, junto con los principios de eficiencia, eficacia y costo-beneficio, enfatizando su importancia para priorizar acciones, evaluar el impacto y asegurar que el plan de mercadeo responda a los objetivos propuestos.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
