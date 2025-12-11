<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p El componente formativo aborda el fenómeno de la migración desde su contexto social y emocional, analizando sus causas, tipos y los impactos psicosociales que experimentan tanto las personas migrantes como las comunidades de acogida. Además, presenta el marco normativo internacional y nacional que garantiza la protección de sus derechos, destacando la importancia del acompañamiento institucional y la atención psicosocial con enfoque diferencial. De esta manera, se promueve una comprensión integral de la movilidad humana y se fortalece la capacidad para brindar apoyo adecuado, inclusivo y respetuoso de la dignidad humana en los procesos de integración y retorno.    

    .row.justify-content-center
      .col-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis se describe de manera organizada la relación entre la migración, sus impactos psicosociales y el marco legal que protege los derechos de las personas migrantes y retornadas. Se presentan los principales instrumentos internacionales y nacionales que orientan la atención integral, resaltando la importancia de un acompañamiento emocional, social y comunitario para favorecer la inclusión y el bienestar de las poblaciones en situación de movilidad humana.")
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
