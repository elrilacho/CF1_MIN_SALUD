<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .contenido_curso
    .mn.py-0 
      .titulo-principal.mb-5
          .titulo-principal__numero
            span 1
          h1 Normas a nivel nacional e internacional en atención a población LGTBIQ+
    .mn.p-lg-0.p-5.mb-5(style="background-color: #e9fcf6 ")
      .row.justify-content-center.align-items-center
        .col-lg-6.mb-lg-0.mb-5
          p.mb-0.ps-lg-5.ms-lg-5 Es fundamental realizar un recorrido por las normas y lineamientos internacionales que han servido de marco en nuestro país para el diseño e implementación de acciones dirigidas a garantizar un trato digno, cálido, humanizado y seguro en la prestación del servicio de salud a las personas de los sectores LGBTIQ+, desde su ingreso hasta el egreso del mismo.
        .col-lg-6: img(src='@/assets/curso/2.png', alt='')
    .bg-tema-1.mn
      #t_1_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
        h2 1.1 Lineamientos internacionales: atención a población de los sectores LGBTIQ+
      p.mb-5(data-aos='fade-right') Las normas establecidas a nivel internacional para eliminar la discriminación y violencia contra las personas de los sectores LGBTIQ* y otras disidencias de género han evolucionado con el tiempo, centrándose y especializándose en temas críticos que requieren protección. #[span.color-primario Su objetivo principal es determinar las obligaciones de los países para garantizar estos derechos.] Realizaremos un breve recorrido por las más importantes, que son relevantes para el contexto de este curso:
      .row.justify-content-center.mb-5
        .col-lg-8.mb-lg-0.mb-3(data-aos="fade-right")
          h5 En primer lugar: 
          p #[span.color-primario La Organización de las Naciones Unidas], a través de la Declaración Universal de Derechos Humanos, ha establecido lineamientos para la adopción de estrategias territoriales y de cooperación internacional con el fin de garantizar los derechos de la población, #[span.color-primario respetando su diversidad y la pluralidad de identidades que caracterizan a los grupos y sociedades que conforman la humanidad.] Dentro de los 30 artículos que contiene la Declaración, es crucial, en el contexto de este curso, destacar el Artículo 25, que hace referencia: 
          .tarjeta(style="background-color: #2c3e50").tarjeta-cita.p-5
            .tarjeta-cita__comilla1: img(src='@/assets/curso/comilla1.svg', alt='')
            .tarjeta-cita__comilla2: img(src='@/assets/curso/comilla2.svg', alt='') 
            p.text-white.fst-italic.mt-3 “Toda persona tiene derecho a un nivel de vida adecuado que le asegure, así como a su familia, la salud y el bienestar, y en especial la alimentación, el vestido, la vivienda, la asistencia médica y los servicios sociales necesarios; tiene asimismo derecho a los seguros en caso de desempleo, enfermedad, invalidez, viudez, vejez u otros casos de pérdida de sus medios de subsistencia por circunstancias independientes de su voluntad”.
            p(style="color: #A7F7DD") Declaración Universal de los Derechos Humanos (1948). Artículo 25
        .col-lg-4.col-7(data-aos="fade-left"): img(src='@/assets/curso/3.png', alt='')
      p.mb-5(data-aos='fade-right') En el ámbito de los derechos humanos, la labor de las instituciones internacionales es fundamental para guiar y educar a los Estados en la protección y promoción de la población LGTBIQ+. #[span.color-primario El siguiente video detalla algunas normas más significativas:] 
      figure.mb-5
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Video: Leyenda del video
    .mn.mb-5(style="background-color: #3c1c74 ").py-0
      .row.justify-content-center.align-items-center
        .col-lg-7.mb-lg-0.mb-5(data-aos="fade-right")
          p.mb-0.text-white.p-4 El Programa de las Naciones Unidas para el Desarrollo (PNDU) manifestó su compromiso de ejercer el liderazgo para la inclusión de personas LGBTI, estrategia que contempla 5 dimensiones catalogadas como prioritarias y evaluadas mediante el índice de inclusión. Según la Nota Conceptual del Índice de Inclusión LGBTI, (2016), las estrategias corresponden con: 
        .col-lg-5.col-7: img(src='@/assets/curso/4.svg', alt='' style="margin-top: -2rem")
    .row.justify-content-center.mb-5.g-2
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.tarjeta-icono.p-4
          img(src='@/assets/curso/5.svg', alt='').me-2
          p.mb-0 Participación política y cívica. 
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.tarjeta-icono.p-4
          img(src='@/assets/curso/6.svg', alt='').me-2
          p.mb-0 Bienestar económico. 
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.tarjeta-icono.p-4
          img(src='@/assets/curso/7.svg', alt='').me-2
          p.mb-0 Seguridad personal y violencia. 
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.tarjeta-icono.p-4
          img(src='@/assets/curso/8.svg', alt='').me-2
          p.mb-0 Salud y educación
    p.mb-5(data-aos='fade-right') A continuación, se presenta un resumen con otras normas internacionales de derechos humanos frente a la eliminación de la violencia y discriminación hacia las personas que componen los sectores LGBTIQ+, y orientaciones sexuales e identidades de género no hegemónicas, las cuales puede consultar para ampliar la información al respecto:
    .bg-info.mn.pb-0
      ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/9.svg', alt='Texto que describa la imagen')
          .tarjeta.color-acento-botones.p-3(x="20%" y="20%" numero="+")
            .h5.mb-2 titulo
            p Lorem ipsum dolor Curabitur vestibulum tortor quis nisi

  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({}),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
