<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 11
      h1 Reconocimiento del manejo interno y externo de los residuos.

    figure.mb-4
      img(src='@/assets/curso/tema11/1.png', alt='Texto que describa la imagen')

    p.mb-4 Identificar en el diagnóstico si se realizan prácticas de prevención y minimización como las estrategias más usadas para prevenir o minimizar la generación de residuos se encuentran las siguientes: 
    separador

    #t_11_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 11.1 Reconocimiento del manejo interno.

    .row.align-items-center.mb-4 
      .col-lg-6
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-2
          p.mb-0 Aplicar conceptos de producción limpia, sustitución de materias primas, modificación del proceso productivo, modificación o inclusión de equipos auxiliares, sustitución o modificación del producto, segregación de los residuos, almacenamiento adecuado, buenas prácticas operacionales, rehusó como materia prima en el proceso de origen, reciclaje interno en la organización para subproductos o para aprovechamiento interno.
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema11/1.jpg', alt='Texto que describa la imagen')
    separador

    #t_11_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 11.2 Reconocimiento del manejo interno.

    .row.align-items-center.mb-4 
      .col-lg-6
        p.mb-2 En la recolección externa se requiere realizar con gestores autorizados si son de materiales reciclables deben estar legalmente constituidas y demostrar en la cámara de comercio que tienen esa función de ese residuo en particular y generar la respectiva factura y posteriormente el certificado en donde indique la cantidad y con qué fin se dispuso como materia prima de qué, si es no aprovechable no peligroso con las entidades de servicio público e internamente llevar su peso, si es residuo peligroso con entidades autorizadas por la autoridad ambiental que cuenten con licencia ambiental, si es para transportar únicamente o también como gestor del tratamiento y disposición final y esta esté vigente, solicitar el flete, el debido certificado al transportista de la entrega del residuo al gestor ambiental y si es el gestor ambiental su certificado de disposición final y/o tratamientos.
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema11/2.jpg', alt='Texto que describa la imagen')
    separador

    #t_11_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 11.3 Aprovechamiento.

    figure.mb-2
      img(src='@/assets/curso/tema11/2.png', alt='Texto que describa la imagen')
    p.mb-4  Se recomienda identificar si se está realizando el aprovechamiento de residuos al interior o al exterior de la organización y establecer el tipo de técnica o proceso, el tipo de residuo y el producto final que se obtiene.
    separador

    #t_11_4.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 11.4 Aprovechamiento.

    .tarjeta.color-cuadro2.p-4.mb-4
      .row.align-items-center
        .col-lg-6
          p.mb-0  Determinar si se está dando algún tipo de tratamiento a los residuos generados, en caso afirmativo, definir qué proceso usa para cada tipo de residuo y si se realiza al interior o al exterior de la organización. 
        .col-lg-6
          figure.mb-2
            img(src='@/assets/curso/tema11/3.png', alt='Texto que describa la imagen')
    separador

    #t_11_5.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 11.5 Aprovechamiento.

    .tarjeta.color-cuadro2.p-4.mb-4
      .row.align-items-center
        .col-lg-6
          figure.mb-2
            img(src='@/assets/curso/tema11/4.png', alt='Texto que describa la imagen')
        .col-lg-6
          p.mb-0  Determinar si se está dando algún tipo de tratamiento a los residuos generados, en caso afirmativo, definir qué proceso usa para cada tipo de residuo y si se realiza al interior o al exterior de la organización. 
    
   
</template>

<script>
export default {
  name: 'Tema11',
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
