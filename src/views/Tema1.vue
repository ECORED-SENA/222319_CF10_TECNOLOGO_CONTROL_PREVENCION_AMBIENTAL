<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Introducción importancia del diagnóstico de los residuos

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        p.mb-4 Pensar en la basura genera un rechazo inmediato, sin embargo, se debe convivir con ella y no solo en los hogares, sino a la vuelta de cualquier esquina. Todo esto es el resultado de las diversas actividades que realiza el hombre en su diario vivir, donde produce una cantidad excesiva de desechos, los cuales se convierten en un inconveniente mayor en su almacenamiento, disposición o eliminación. Es por esto que es necesario aprender a manejar y aprovechar adecuadamente las basuras que se producen, no verlas como en la actualidad y verlas como residuos que son objetos y que se puede transformar en otro bien con valor económico, en especial los sólidos.
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4
          p.mb-0 Por tanto, es importante realizar el diagnóstico de los residuos en un lugar determinado para así crear estrategias que prevengan y minimicen el impacto de los residuos y no se genere una problemática socio ambiental, aparte de esto en la sociedad existen comunidades de bajos ingresos que viven y se alimentan de los residuos, lo cual también requiere de una gestión socio ambiental.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema1/img1.jpg', alt='Texto que describa la imagen')

    .row.mb-4
      .col-lg-1
        span
      .col-lg-11
        p.mb-0 Para complementar la información se pueden visualizar los siguientes videos:

    .row 
      .col-lg-12
        .tarjeta.color-azul.p-4
          .row.align-items-center
            .col-lg-1
              figure
                img(src='@/assets/curso/tema1/icon1.png', alt='Texto que describa la imagen')
            .col-lg-11
              .row
                .col-lg-12
                  p.text-white <b>Para profundizar en el tema, se invita a revisar la sección de materiales complementarios, donde encontrará los videos: Puntaje Nacional Chile (4 abril 2013), denominado “Unidades de concentración” y otros objetos de aprendizaje que son de sumo interés para su aprendizaje.</b>
                .col-lg-6
                  a.anexo.mb-4.mb-lg-0(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p <FONT COLOR="#006DF0"> <b>Enlace web.</b> Guion_instruccional_CF10_V20202   Recurso No. 2 </FONT> 
                .col-lg-6
                  a.anexo.mb-4.mb-lg-0(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p <FONT COLOR="#006DF0"> <b>Enlace web.</b> Guion_instruccional_CF10_V20202   Recurso No. 3 </FONT> 



  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
