<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Realizar el diagnóstico

    figure.mb-4
      img(src='@/assets/curso/tema6/1.png', alt='Texto que describa la imagen')   

    p.mb-4 El diagnóstico de los residuos realiza la caracterización cualitativa y cuantitativa de los residuos se identifican oportunidades de mejora en la gestión de los residuos actuales, ver figura 5.

    .row.justify-content-center
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 5
          span Esquema de elaboración de un diagnóstico ambiental de residuos
        figure.mb-2
          img(src='@/assets/curso/tema6/fig1.svg', alt='Texto que describa la imagen')
        figcaption Nota. Esquema para la elaboración del manejo integral de residuos. Universidad Pontificia Bolivariana y Área metropolitana del valle de aburra (2008).


</template>

<script>
export default {
  name: 'Tema6',
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
