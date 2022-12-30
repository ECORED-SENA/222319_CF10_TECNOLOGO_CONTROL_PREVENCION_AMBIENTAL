<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Conceptos generales

    p.mb-4 En la aplicación del presente componente formativo se tendrán en cuenta las siguientes definiciones establecidas en la normatividad vigente:

    .row.justify-content-center.mb-4
      .col-lg-8
        .row
          .col-lg-4.col-md-6.col-8
            .tarjeta.color-primario.p-3.mb-4
              h4.mb-0 Definiciones (ver figura 1). 
          .col-lg-12
            .titulo-sexto.color-acento-contenido
              h5 Figura 1
              span Jerarquía en la gestión de residuos
          figure.mb-2
            img(src='@/assets/curso/tema2/fig1.svg', alt='Texto que describa la imagen')
          figcaption Nota. Guía para el manejo integral de residuos. Universidad Pontificia Bolivariana y Área metropolitana del valle de aburra (2008).

    .row.align-items-center.mb-4
      .col-lg-6
        LineaTiempoD.color-primario.mb-4
          .row(numero="1" titulo="Residuo sólido o desecho")
            .col-md-12
              p Es cualquier objeto, material, sustancia o elemento sólido resultante del consumo o uso de un bien en actividades domésticas, industriales, comerciales, institucionales, de servicios, que el generador abandona, rechaza o entrega y que es susceptible de aprovechamiento o transformación en un nuevo bien, con valor económico o de disposición final (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p. 4).

          .row(numero="2" titulo="Residuo sólido aprovechable")
            .col-md-12
              p Es cualquier material, objeto, sustancia o elemento sólido que no tiene valor de uso directo o indirecto para quien lo genere, pero que es susceptible de incorporación a un proceso productivo (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p. 4).

          .row(numero="3" titulo="Residuo sólido no aprovechable")
            .col-md-12
              p Es todo material o sustancia sólida o semisólida de origen orgánico e inorgánico, putrescible o no, proveniente de actividades domésticas, industriales, comerciales, institucionales, de servicios, que no ofrece ninguna posibilidad de aprovechamiento, reutilización o reincorporación en un proceso productivo. Son residuos sólidos que no tienen ningún valor comercial, requieren tratamiento y disposición final y por lo tanto generan costos de disposición (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p. 4). 

          .row(numero="4" titulo="Residuo peligroso")
            .col-md-12
              p Es aquel que, por sus características infecciosas, tóxicas, explosivas, corrosivas, inflamables, volátiles, combustibles, radiactivas o reactivas puedan causar riesgo a la salud humana o deteriorar la calidad ambiental hasta niveles que causen riesgo a la salud humana. También son residuos peligrosos aquellos que sin serlo en su forma original se transforman por procesos naturales en residuos peligrosos (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p. 4).

          .row(numero="5" titulo="Residuos anatomopatológicos")
            .col-md-12
              p Son aquellos residuos como partes del cuerpo, muestras de órganos, tejidos o líquidos humanos, generados con ocasión de la realización de necropsias, procedimientos médicos, remoción quirúrgica, análisis de patología, toma de biopsias o como resultado de la obtención de muestras biológicas para análisis químico, microbiológico, citológico o histológico (Ministerio de salud y protección social, 2016).

          .row(numero="6" titulo="Residuos no peligrosos")
            .col-md-12
              p Son aquellos producidos por el generador en desarrollo de su actividad, que no presentan ninguna de las características de peligrosidad (Ministerio de salud y protección social, 2016).
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/img1.jpg', alt='Texto que describa la imagen')
    .row.align-items-center.mb-4
      .col-lg-6
        figure.mb-4 
          img(src='@/assets/curso/tema2/img2.jpg', alt='Texto que describa la imagen')
      .col-lg-6
        LineaTiempoD.color-primario
          .row(numero="7" titulo="Residuos especiales")
            .col-md-12
              p Son aquellos residuos que por su naturaleza, composición, tamaño, volumen y peso no puedan ser recolectados, manejados, tratados o dispuestos normalmente por la persona prestadora del servicio. Incluye los residuos producto de las actividades de corte de césped y poda de árboles ubicados en las vías y áreas públicas; aquellos provenientes del barrido y limpieza de vías y áreas públicas, y los residuos provenientes de actividades de construcción y demás obras civiles. (Área metropolitana del Valle de Aburra, 2016, p.8)

          .row(numero="8" titulo="Lixiviado")
            .col-md-12
              p Es el líquido residual generado por la descomposición biológica de la parte orgánica o biodegradable de los residuos sólidos bajo condiciones aeróbicas o anaeróbicas y/o como resultado de la percolación de agua a través de los residuos en proceso de degradación (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p.4).

          .row(numero="9" titulo="Reciclaje")
            .col-md-12
              p Es el proceso mediante el cual se aprovechan y transforman los residuos sólidos recuperados y se devuelve a los materiales su potencialidad de reincorporación como materia prima para la fabricación de nuevos productos. El reciclaje puede constar de varias etapas: procesos de tecnologías limpias (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p.4).

          .row(numero="10" titulo="Reutilización")
            .col-md-12
              p Es la prolongación y adecuación de la vida útil de los residuos sólidos recuperados y que mediante procesos, operaciones o técnicas devuelven a los materiales su posibilidad de utilización en su función original o en alguna relacionada, sin que para ello requieran procesos adicionales de transformación (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p.4).

          .row(numero="11" titulo="Disposición final")
            .col-md-12
              p Es el proceso de aislar y confinar los residuos o desechos peligrosos, en especial los no aprovechables, en lugares especialmente seleccionados, diseñados y debidamente autorizados, para evitar la contaminación y los daños o riesgos a la salud humana y al ambiente (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2015).

          .row(numero="12" titulo="Separación en la fuente")
            .col-md-12
              p Es la clasificación de los residuos sólidos en el sitio donde se generan para su posterior recuperación (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p.4).

          .row(numero="13" titulo="Generador o productor")
            .col-md-12
              p Persona que produce residuos sólidos y es usuario del servicio (Ministerio de Ambiente Vivienda y Desarrollo Territorial, 2002, p.3).
   
   
</template>

<script>
export default {
  name: 'Tema2',
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
