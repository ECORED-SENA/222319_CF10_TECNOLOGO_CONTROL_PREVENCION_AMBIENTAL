<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 9
      h1 Reconocimiento de la recolección de los residuos

    p.mb-4 Se recomienda establecer la existencia y ubicación de las rutas de recolección dentro de la organización, evaluando las características que debe cumplir como, ver tabla 7:

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. Área metropolitana del valle de aburra (2016).
            thead
              tr
                th(style='background-color: #DFF2ED').anch DESCRIPCIÓN
                th(style='background-color: #DFF2ED') CUMPLE
                th(style='background-color: #DFF2ED') NO CUMPLE
              tr(style='background-color: #FFFFFF')
                td 1. Tiene definidas rutas de recolección. 
                td 
                td 
              tr(style='background-color: #FFFFFF')
                td 2. Establece horarios y frecuencias de recolección.
                td 
                td 
              tr(style='background-color: #FFFFFF')
                td 3. Realiza la recolección selectiva de los residuos en los puntos de generación.
                td 
                td 
              tr(style='background-color: #FFFFFF')
                td 4. Los elementos empleados para la recolección de residuos peligrosos son de uso exclusivo para este fin. 
                td 
                td 
              tr(style='background-color: #FFFFFF')
                td 5. Las personas que realizan esta actividad cuentan con los elementos de protección personal necesarios como tapabocas, guantes, gafas, etc.
                td 
                td 
              tr(style='background-color: #FFFFFF')
                td 6. En caso de ser necesario (por cantidades, distancias y tipo de residuos) se cuenta con equipos de cargue y movilización.
                td 
                td 
    .row.mb-4
      .col-lg-5.col-md-6.col-8
        .tarjeta.color-verde3.p-2.mb-0
          p.mb-0 <b>Ruta de recolección de residuos</b>

    p.mb-4 La organización requiere tener un plano de ruta de recolección de residuos en donde se identifique los puntos de recolección y sus recipientes, la capacidad de los recipientes, los carros recolectores, las rutas de recolección trazadas de los tipos de residuos mínimo una para peligrosos y una para no peligrosos, en la de no peligrosos muchas veces se divide en dos una de residuos no aprovechables y otra de residuos aprovechables y los horarios de recolección, ver figuras 25, 26 y 27.

    .row.justify-content-center.mb-4
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 25  
          span Ruta sanitaria ejemplo 1
        figure.mb-0
          img(src='@/assets/curso/tema9/1.jpg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Universidad Pontificia Bolivariana y Área metropolitana del valle de aburra (2008).
    
    .row.justify-content-center.mb-4
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 26
          span Ejemplo Ruta sanitaria 
        figure.mb-0
          img(src='@/assets/curso/tema9/2.jpg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Área Metropolitana de Bucaramanga (2002). 

    .row.justify-content-center.mb-4
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 27
          span Ejemplo ruta sanitaria laboratorio  
        figure.mb-0
          img(src='@/assets/curso/tema9/3.jpg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Empresa de acueducto y alcantarillado y aseo de Madrid. (2018 ).

</template>

<script>
export default {
  name: 'Tema9',
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
