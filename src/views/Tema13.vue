<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 13
      h1 Informe de Diagnóstico de Residuos.

    p.mb-4 En el diagnóstico se debe establecer información sobre el funcionamiento de la organización y la descripción general del proceso productivo. En la siguiente tabla 11, se presentan algunos de los puntos que se deben decir en un diagnóstico de residuos: 

    .titulo-sexto.color-acento-contenido.mb-2
      h5 Tabla 11      
      span Pasos para desarrollar el diagnóstico de la organización
    .tabla-a.color-acento-botones.mb-5 
      table
        caption Nota. Universidad Pontificia Bolivariana y Área metropolitana del valle de aburra (2008). 
        thead
          tr
            th(style='background-color: #DFF2ED') Pasos
            th(style='background-color: #DFF2ED') Componente del diagnóstico
            th(style='background-color: #DFF2ED').anch Descripción
          tr(style='background-color: #FFFFFF')
            <td rowspan="6">PASO 1</td>
            <td rowspan="6">Información general.</td> 
          tr(style='background-color: #FFFFFF')
            td Describir la actividad que desarrolla, operaciones involucradas, jornadas laborales.
          tr(style='background-color: #FFFFFF')
            td Número de personas que habitan, laboran, acuden, estudian o visitan las instalaciones de la organización.
          tr(style='background-color: #FFFFFF')
            td Describir las dependencias con las que cuenta y los procesos productivos que se llevan a cabo.
          tr(style='background-color: #FFFFFF')
            td Describir mediante flujogramas las materias primas e insumos utilizados, los productos elaborados y los residuos generados.
          tr(style='background-color: #FFFFFF')
            td Cuantificar los residuos generados a partir de la tarifa de aseo en un período de tiempo no menor a seis meses.
          tr(style='background-color: #FFFFFF')
            <td rowspan="3">PASO 2</td>
            <td rowspan="3">Generación de residuos sólidos.</td> 
          tr(style='background-color: #FFFFFF')
            td Identificar los puntos de generación de residuos sólidos como zona de bodega o almacenamiento, planta de producción, oficinas, cocineta, punto de ventas, etc.
          tr(style='background-color: #FFFFFF')
            td Identificar, clasificar y cuantificar los residuos peligrosos y no peligrosos generados, de acuerdo con los conocimientos básicos.
          tr(style='background-color: #FFFFFF')
            <td rowspan="4">PASO 3</td>
            <td rowspan="4">Almacenamiento de los residuos sólidos.</td> 
          tr(style='background-color: #FFFFFF')
            td Describir cómo son los sitios de almacenamiento temporal y almacenamiento definitivo de los residuos sólidos en la organización.
          tr(style='background-color: #FFFFFF')
            td Describir las técnicas y los horarios de recolección y transporte interno de los residuos desde los puntos de almacenamiento temporal hasta el sitio de almacenamiento definitivo.
          tr(style='background-color: #FFFFFF')
            td Elaborar un mapa con los sitios de almacenamiento temporal y definitivo, además de la ruta establecida para recolección de los residuos sólidos.
          tr(style='background-color: #FFFFFF')
            <td rowspan="5">PASO 4</td>
            <td rowspan="5">Caracterización y aforo de los residuos generados.</td> 
          tr(style='background-color: #FFFFFF')
            td Realizar el aforo de los residuos no peligrosos y peligrosos generados en un período de tiempo que corresponda con los procesos productivos de la organización.
          tr(style='background-color: #FFFFFF')
            td Realizar la caracterización física de los residuos no peligrosos y los peligrosos generados en un período de tiempo que corresponda con los procesos productivos de la organización.
          tr(style='background-color: #FFFFFF')
            td Describir si existe aprovechamiento de los residuos sólidos ya sea mediante reciclaje, reutilización o compostaje.
          tr(style='background-color: #FFFFFF')
            td Elaborar informe de caracterización.
          tr(style='background-color: #FFFFFF')
            td PASO 5
            td Clasificación de tipo de generador.
            td Clasificar como generador a la organización a partir de la cantidad de residuos peligrosos y no peligrosos generados de acuerdo con el Decreto 4741 de 2005 y la Resolución CRA 351 de 2005, respectivamente.
          tr(style='background-color: #FFFFFF')
            td PASO 6
            td Alternativas de manejo externo de los residuos generados.
            td 
              p.mb-2 Describir las diferentes alternativas de manejo externo de los residuos peligrosos y no peligrosos, ya sean:
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  p.mb-0 Reciclaje.
                li 
                  i.fas.fa-check
                  p.mb-0 Reutilización.
                li 
                  i.fas.fa-check
                  p.mb-0 Compostaje.
                li 
                  i.fas.fa-check
                  p.mb-0 Incineración.
                li 
                  i.fas.fa-check
                  p.mb-0 Inertización.
                li 
                  i.fas.fa-check
                  p.mb-0 Otros.
          tr(style='background-color: #FFFFFF')
            td PASO 7
            td Plan de Contingencias.
            td Determinar la existencia o no, de medidas de contingencia para prevenir o contener accidentes en el manejo de los residuos sólidos, sean internas o externas.
          tr(style='background-color: #FFFFFF')
            td PASO 8
            td Registro fotográfico.
            td Elaborar un registro fotográfico del diagnóstico levantado.
          tr(style='background-color: #FFFFFF')
            td PASO 9
            td Análisis y conclusiones.
            td Analizar y concluir sobre la información obtenida durante el diagnóstico, de tal manera que se establezca la situación actual de la organización.

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla_11
                  p Pasos para desarrollar el diagnóstico de la organización.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    figure.mb-4
      img(src='@/assets/curso/tema13/1.png', alt='Texto que describa la imagen')
    p.mb-4 Los resultados obtenidos del diagnóstico permiten la definición de una línea base sobre el manejo de los residuos sólidos, logrando conocer cualitativa y cuantitativamente los residuos generados y cuál es su manejo actual. Con este diagnóstico se podrán establecer propuestas de solución medidas de prevención y mitigación de los residuos, el cual se establecen como plan de acción de la gestión de los residuos.
       
            
          
</template>

<script>
export default {
  name: 'Tema13',
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
