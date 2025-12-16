<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-5(data-aos="fade-down") La migración es un fenómeno social y humano que implica el desplazamiento de personas en busca de mejores condiciones de vida. Este componente aborda el análisis de la política migratoria y del marco legal que orienta la atención psicosocial dirigida a la población migrante, la población colombiana retornada y las comunidades de acogida.
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3.col-8.col-md-7.order-lg-1.order-1.mb-3
        figure
          img(src='@/assets/curso/temas/intro/img01.svg', alt='Imagen decorativa')
      .col-lg-7.col-12.order-lg-2.order-2
        .tarjeta.tarjeta--C01.p-3.mb-3
          p.mb-0(data-aos="fade-down") A lo largo de este estudio, el aprendiz comprende cómo las políticas migratorias, los derechos humanos y los principios humanitarios guían las acciones de protección, asistencia e inclusión social en contextos de movilidad humana.
        p(data-aos="fade-down") Asimismo, se profundiza en la Política Integral Migratoria de Colombia, en los tratados y convenciones internacionales sobre migración y refugio, y en los derechos y deberes que sustentan la atención psicosocial desde un enfoque ético, intercultural y basado en derechos humanos.
        p.mb-0(data-aos="fade-down") Para comprender la importancia del contenido y los temas abordados, se recomienda acceder al siguiente video:
    .row.justify-content-center.align-items-center           
      .col-lg-12
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/721LyzzIUGQ?si=9AJrDjaUmzGTDyN9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
