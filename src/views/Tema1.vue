<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 1
      h1 Contexto general de la migración y su impacto psicosocial
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img01.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0(data-aos="fade-down") La migración es un fenómeno humano y social complejo que ha acompañado a la humanidad a lo largo de su historia. Implica el desplazamiento de personas o grupos desde un lugar de origen hasta un nuevo destino, de manera temporal o permanente, motivado por razones económicas, políticas, sociales, ambientales o de seguridad (OIM, 2019). Este proceso, además de modificar la estructura demográfica de los países, transforma las dinámicas familiares, la cultura, los valores comunitarios y las percepciones de identidad tanto en la población migrante como en las comunidades receptoras.
    p.mb-5(data-aos="fade-down") Este fenómeno no se reduce únicamente al movimiento físico entre territorios, sino que también constituye una experiencia emocional profunda que puede generar esperanza, incertidumbre, pérdida y adaptación. El aumento constante de los desplazamientos humanos en las últimas décadas refleja la persistencia de factores como la desigualdad, los conflictos armados, los desastres naturales y las crisis económicas globales. Según Naciones Unidas (s. f.), más de 280 millones de personas viven actualmente fuera de su país de origen, lo que evidencia la magnitud de esta realidad global.
    .row.justify-content-center.mb-4
      .col-lg-8.order-lg-2.order-2
        .cajon.cajon.C01.color-primario.px-3.py-4.mb-4
          p(data-aos="fade-down") En Colombia, la migración se caracteriza por su multidimensionalidad: el país es simultáneamente territorio de origen, tránsito, destino y retorno. Históricamente, ha experimentado la salida de nacionales por motivos económicos y de seguridad; al mismo tiempo, se ha consolidado como lugar de acogida para personas extranjeras, especialmente provenientes de Venezuela. Esta dinámica plantea importantes retos en materia de derechos humanos, atención humanitaria, inclusión social y acompañamiento psicosocial (DNP, 2022).
        p.mb-0(data-aos="fade-down") El impacto psicosocial de la migración se refleja en la manera en que las personas enfrentan los cambios y desafíos que se derivan del proceso migratorio. El duelo por lo dejado, la nostalgia, el estrés de adaptación y la ruptura de redes de apoyo pueden afectar la salud mental e influir en la integración social. A su vez, las comunidades receptoras pueden experimentar tensiones asociadas a la diversidad cultural o a la percepción de competencia por los recursos, lo que exige promover acciones que fortalezcan el respeto, la empatía y la convivencia.
      .col-lg-4.order-lg-1.order-1.mb-3.col-md-5.col-7
        figure(data-aos="fade-up") 
          img(src='@/assets/curso/temas/tema1/img02.svg', alt='Imagen decorativa')
    p.mb-0(data-aos="fade-down") Por ello, comprender el contexto de la migración permite analizar sus causas, sus efectos y las respuestas institucionales orientadas a una atención psicosocial basada en los derechos humanos, la equidad y la dignidad de las personas (ACNUR, 2017).
    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.1 Causas y tipos de migración
    p(data-aos="fade-down") Colombia ocupa un lugar particular dentro de la dinámica migratoria mundial, al actuar simultáneamente como país de origen, tránsito, destino y retorno. Esto implica que miles de colombianos migran al exterior por razones sociales, económicas o de seguridad, mientras que el país también recibe un número creciente de personas extranjeras, principalmente provenientes de Venezuela (DNP, 2022).
    p.mb-5(data-aos="fade-down") Según la Organización Internacional para las Migraciones (OIM, 2023), en Colombia residen más de 2,8 millones de personas migrantes, siendo la mayoría de nacionalidad venezolana. Esta realidad plantea desafíos en materia de:
    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img03.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Acceso a servicios básicos (salud, educación y alimentación).
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img04.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Inclusión laboral y económica.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img05.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Garantías de protección y regularización migratoria.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img06.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Integración comunitaria y convivencia intercultural.
    .row.justify-content-center
      .col-lg-10.col-12
        p.mb-5(data-aos="fade-down") Además, Colombia también enfrenta el fenómeno del retorno, es decir, el regreso de nacionales que residían en otros países y vuelven por motivos como los establecidos en la Ley 1565 de 2012:
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        .row.justify-content-center
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img07.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100
                  h5 Crisis económicas en los lugares de destino.
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img08.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100
                  h5 Reunificación familiar.
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img09.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100.mb-0
                  h5 Dificultades para regularizar su estatus migratorio.
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img10.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100
                  h5 Situaciones de discriminación o inseguridad.
    p.mb-5(data-aos="fade-down") El país ha adoptado medidas normativas y humanitarias para garantizar los derechos de las personas migrantes y retornadas, entre ellas:
    .row.justify-content-center.mb-0(data-aos="flip-down")
      .col-xl-4.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img11.svg", alt="alt").img130.m-auto
          h4.text-center Ley 2136 de 2021
          p.mb-0 Política Integral Migratoria. Promueve una movilidad humana ordenada, segura y regular, basada en la inclusión social, el acceso a derechos y la atención psicosocial.
      .col-xl-4.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img12.svg", alt="alt").img130.m-auto
          h4.text-center Decreto 216 de 2021
          p.mb-0 Estatuto Temporal de Protección para Migrantes Venezolanos (ETPV). Facilita la regularización migratoria y el acceso a salud, educación y empleo formal.
      .col-xl-4.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img13.svg", alt="alt").img130.m-auto
          h4.text-center CONPES 4100 de 2022
          p.mb-0 Articula las acciones institucionales para fortalecer la integración y el bienestar de la población migrante.
    .row.justify-content-center
      .col-lg-10.col-12
        p.mb-5(data-aos="fade-down") Estas políticas se complementan con acciones territoriales y comunitarias orientadas a fortalecer la convivencia y la cohesión social.
        .cajon.cajon.C01.color-primario.p-4.mb-3
          p.mb-0(data-aos="fade-down") La gestión migratoria no depende únicamente de políticas públicas, sino también de una mirada humana y un enfoque psicosocial. Reconocer las emociones, desafíos y expectativas de las personas que llegan o regresan permite construir comunidades más solidarias, respetuosas e inclusivas. La migración y el retorno deben comprenderse como procesos profundamente humanos que requieren protección jurídica y acompañamiento emocional para garantizar la dignidad y el bienestar (ACNUR y OIM, 2023).
    separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.2 Migración internacional y retorno en Colombia
    .row.justify-content-center.mb-5
      p.mb-5(data-aos="fade-down") Colombia enfrenta dos fenómenos paralelos dentro de la movilidad humana. Por un lado, se presenta la llegada de personas migrantes internacionales, principalmente provenientes de Venezuela. Por otro, se evidencia el retorno de ciudadanos colombianos que residían en otros países y regresan ante diversas circunstancias. Ambos grupos comparten retos significativos relacionados con la integración laboral, el acceso a salud y educación, el reconocimiento de competencias, la estabilidad económica y la regularización migratoria.
      .col-lg-7.order-lg-1.order-2
        p.mb-4(data-aos="fade-down") Estos procesos generan transformaciones sociales tanto en las familias como en las comunidades receptoras. En el caso de la población retornada, la adaptación puede implicar la reconstrucción de redes de apoyo, la validación de títulos o la inserción en entornos laborales desconocidos. Para la población extranjera, el proceso de integración puede verse marcado por barreras culturales, discriminación, estigmatización y dificultades para acceder a servicios básicos, lo que puede afectar su bienestar emocional y social.
        .cajon.cajon.C01.color-primario.p-4.mb-3
          p.mb-0(data-aos="fade-down") El Estado colombiano ha establecido mecanismos normativos y de acompañamiento como la Política Integral Migratoria (Ley 2136 de 2021) y el Estatuto Temporal de Protección para Migrantes Venezolanos (Decreto 216 de 2021), que buscan garantizar el reconocimiento de derechos, la regularización y la inclusión social. Asimismo, el CONPES 4100 de 2022 orienta acciones interinstitucionales para la atención y la integración de estas poblaciones.
      .col-lg-5.order-lg-2.order-1.mb-3.col-md-5.col-7
        figure(data-aos="fade-up") 
          img(src='@/assets/curso/temas/tema1/img14.png', alt='Imagen decorativa')
    .row.justify-content-center
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") Sin embargo, debido a la magnitud y complejidad del fenómeno migratorio, es necesario fortalecer la articulación entre entidades nacionales y territoriales, así como la participación comunitaria. La implementación de un enfoque psicosocial es fundamental para promover una convivencia armónica, reducir situaciones de vulnerabilidad y acompañar los procesos de adaptación, duelo migratorio y reconstrucción del proyecto de vida de las personas migrantes y retornadas.
    separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.3 Impactos psicosociales de la migración
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img15.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La experiencia migratoria representa un cambio profundo en la vida de las personas, ya que implica dejar atrás el entorno conocido, las redes de apoyo y, en muchos casos, los proyectos personales. Estos procesos generan efectos emocionales, sociales y culturales tanto en quienes migran como en las comunidades involucradas. En este contexto, surgen emociones ambivalentes: esperanza ante nuevas oportunidades, pero también incertidumbre, ansiedad y tristeza asociadas a la separación y al desarraigo (Ministerio de Salud y Protección Social, 2022).
    p(data-aos="fade-down") Desde una perspectiva psicosocial, la migración implica procesos de adaptación individual y colectiva. Quienes migran deben ajustarse a nuevos contextos culturales, aprender normas sociales diferentes y desarrollar estrategias para integrarse en las comunidades receptoras. Este proceso puede generar duelo migratorio, entendido como la reacción emocional ante las pérdidas vinculadas al cambio de país o entorno (Achotegui, 2019). A su vez, las comunidades de acogida también experimentan transformaciones al integrar personas con costumbres, acentos y visiones diversas, lo que puede dar lugar a tensiones, pero también a oportunidades para el aprendizaje intercultural.
    p.mb-5(data-aos="fade-down") Los impactos psicosociales de la migración se manifiestan en diferentes niveles:
    .row.justify-content-center.mb-4
      .col-xl-4.col-lg-6.col-md-10.col-12.mb-xl-0
        .crd_hover_txt.mb-4(data-aos="flip-left")(@mouseover="mostrarIndicador = true")
          .indicador--hover(v-if="mostrarIndicador")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/img16.jpg", alt="Imagen decorativa")
          .crd_hover_txt--body
            h5.t1.mb-3 Individual
            h5.t2.mb-2 Individual
            p.mb-0 Se relacionan con la salud mental, las emociones y la autoestima. Se pueden presentar síntomas como ansiedad, depresión o estrés postraumático, especialmente cuando la migración es forzada.
      .col-xl-4.col-lg-6.col-md-10.col-12.mb-xl-0
        .crd_hover_txt.mb-4(data-aos="flip-left")(@mouseover="mostrarIndicador = true")
          .indicador--hover(v-if="mostrarIndicador")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/img17.jpg", alt="Imagen decorativa")
          .crd_hover_txt--body
            h5.t1.mb-3 Familiar
            h5.t2.mb-2 Familiar
            p.mb-0 Las dinámicas afectivas pueden alterarse debido a la separación o a la reunificación tardía, generando sobrecarga emocional y cambios en los roles.
      .col-xl-4.col-lg-6.col-md-10.col-12.mb-xl-0
        .crd_hover_txt.mb-4(data-aos="flip-left")(@mouseover="mostrarIndicador = true")
          .indicador--hover(v-if="mostrarIndicador")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tema1/img18.jpg", alt="Imagen decorativa")
          .crd_hover_txt--body
            h5.t1.mb-3 Comunitario
            h5.t2.mb-2 Comunitario
            p.mb-0 Las comunidades receptoras pueden enfrentar desafíos de convivencia, prejuicios o xenofobia, mientras que las comunidades de origen pueden experimentar fragmentación social.
    p(data-aos="fade-down") El acompañamiento psicosocial se convierte en un recurso fundamental para promover el bienestar y la integración. Este enfoque facilita el apoyo emocional, el acceso a redes de ayuda y el fortalecimiento de la resiliencia tanto en las personas migrantes como en las comunidades de acogida (PNUD, 2023).
    p.mb-0(data-aos="fade-down") Comprender estos impactos resulta esencial para diseñar intervenciones pertinentes que promuevan la inclusión social y la salud mental. Reconocer las emociones, las pérdidas y las fortalezas que acompañan a la migración constituye el primer paso hacia una atención humana, integral y basada en derechos (Ministerio de Salud y Protección Social, 2022).
    separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.4 Respuesta institucional frente al fenómeno migratorio
    p(data-aos="fade-down") El Estado colombiano, junto con organismos internacionales y entidades territoriales, ha diseñado una respuesta integral para afrontar los desafíos de la migración, orientada a garantizar derechos y promover la integración social de personas migrantes, retornadas y comunidades de acogida (DNP, 2022).
    p.mb-5(data-aos="fade-down") Esta respuesta se organiza a través de:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul" data-aos="zoom-in")
      .row.justify-content-center(titulo="Gobernanza migratoria")
        .col-lg-6.order-lg-1.order-2
          p Basada en los principios del Pacto Mundial para la Migración Segura, Ordenada y Regular (ONU, 2018). Se promueve la coordinación entre niveles de gobierno y la cooperación con organizaciones como:
          .tarjeta--blanca.p-4.mb-4
            ul.lista-ul(data-aos="fade-down")
              li
                i.lista-ul__vineta
                p.mb-0 Organización Internacional para las Migraciones (OIM).
              li
                i.lista-ul__vineta
                p.mb-0 Alto Comisionado de las Naciones Unidas para los Refugiados (ACNUR).
              li.mb-0
                i.lista-ul__vineta
                p.mb-0 Programa de las Naciones Unidas para el Desarrollo (PNUD).
          p Estas instituciones apoyan acciones de regularización, atención psicosocial, fortalecimiento institucional y convivencia social (ACNUR & OIM, 2023).
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          figure
            img(src='@/assets/curso/temas/tema1/img19.jpg', alt="Imagen decorativa")
      .row.justify-content-center(titulo="Atención en salud física y mental")
        .col-lg-6.order-lg-1.order-2
          p El Ministerio de Salud y Protección Social emitió la Circular 035 de 2022 para orientar la atención integral, especialmente en salud mental y acompañamiento psicosocial. Las entidades territoriales desarrollan estrategias para:
          .tarjeta--blanca.p-4.mb-4
            ul.lista-ul(data-aos="fade-down")
              li
                i.lista-ul__vineta
                p.mb-0 Prevención de la violencia.
              li
                i.lista-ul__vineta
                p.mb-0 Apoyo emocional.
              li.mb-0
                i.lista-ul__vineta
                p.mb-0 Fortalecimiento de la convivencia comunitaria.
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          figure
            img(src='@/assets/curso/temas/tema1/img20.jpg', alt="Imagen decorativa")
      .row.justify-content-center(titulo="Rutas de protección y restablecimiento de derechos")
        .col-lg-6.order-lg-1.order-2
          p Entidades como Migración Colombia, ICBF, Cancillería y la Unidad para las Víctimas implementan programas dirigidos a:
          .tarjeta--blanca.p-4.mb-4
            ul.lista-ul(data-aos="fade-down")
              li
                i.lista-ul__vineta
                p.mb-0 Regularización documental.
              li
                i.lista-ul__vineta
                p.mb-0 Protección de niños, niñas y adolescentes.
              li
                i.lista-ul__vineta
                p.mb-0 Restablecimiento de derechos.
              li.mb-0
                i.lista-ul__vineta
                p.mb-0 Reducción de riesgos psicosociales.
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          figure
            img(src='@/assets/curso/temas/tema1/img21.jpg', alt="Imagen decorativa")
    .row.justify-content-center
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") En síntesis, la respuesta institucional trasciende la asistencia inicial y se proyecta hacia la integración social a mediano y largo plazo. La articulación interinstitucional ha permitido fortalecer un modelo de atención centrado en la dignidad humana, el respeto por los derechos y la construcción de comunidades inclusivas y resilientes (ACNUR & OIM, 2023).

</template>

<script>
export default {
  name: 'Tema1',
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
