<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-2.col-6.mb-lg-0.mb-3(data-aos="fade-right"): img(src='@/assets/curso/1.svg' alt='')
      .col-lg-10(data-aos="fade-left")
        p.mb-0 Es un placer para el #[span.color-acento-botones Ministerio de Salud y Protección Social] invitarlos a participar en este curso. El cual tiene como objetivo principal es garantizar que las personas pertenecientes a los sectores LGBTIQ+ y aquellas con orientaciones sexuales e identidades de género no hegemónicas reciban una atención en salud libre de discriminación. Esta atención debe estar alineada con los principios de eficiencia, universalidad, solidaridad, integralidad, unidad y participación, enfocándose principalmente en la persona.
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    
    
</template>

<script>
import BannerInterno from '../components/plantilla/BannerInterno'
export default {
  name: 'Introduccion',
  components: {
    BannerInterno,
  },
  data: () => ({
    globalData: global,
  }),
}
</script>

<style lang="sass"></style>
