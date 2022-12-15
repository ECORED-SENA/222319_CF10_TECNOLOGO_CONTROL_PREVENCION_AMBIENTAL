<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Caracterización y cuantificación de los residuos.

    .row.mb-4
      .col-lg-6
        p.mb-0 Las características de residuos sólidos y los volúmenes de producción varían geográficamente, en función de los hábitos y cultura de la población, sus condiciones socioeconómicas, las condiciones climáticas, así como de la disponibilidad y acceso a materias primas. De estas variaciones se deriva la importancia de los estudios puntuales de caracterización de residuos sólidos, donde se proyecte su gestión exitosa, para de este modo obtener información confiable sobre la cantidad y composición de los materiales, así como de sus opciones de aprovechamiento (Runfola, J., & Gallardo, A., 2009). Un procedimiento de campo utilizado para determinar la cantidad y composición de residuos sólidos en una región es el método del cuarteo, ver figura 21, en términos generales este procedimiento requiere de la descarga y el análisis de una cantidad de residuos en una zona específica (Hidrolab, 2018).
      .col-lg-1
        span
      .col-lg-4
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 21
          span Cuarteo de residuos
        figure.mb-0
          img(src='@/assets/curso/tema8/img1.jpg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Caracterización fisicoquímica residuos sólidos domiciliarios del municipio de Tibasosa. Hidrolab (2018).
    separador

    #t_8_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 8.1 Metodología recomendada para el muestreo, por método de cuarteo para residuos no peligrosos.  

    .row.align-items-center.mb-4
      .col-lg-6
        p.mb-4 Para determinar cualitativa y cuantitativamente los residuos no peligrosos que se generan en la organización es necesario realizar la caracterización y aforo.  En éstos se deben considerar todos los recursos humanos y técnicos disponibles, a fin de favorecer la participación de una buena parte de los empleados que tienen relación directa con el manejo de residuos, lo que permite disminuir los costos totales y adelantar parte del trabajo de formación y educación que son necesarios para el Manejo Integral de Residuos. 
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-0
          p.mb-0 Para garantizar que todos los residuos se vean involucrados en la caracterización y aforo, es necesario identificar todas las actividades o procesos que se ejecutan en la organización y cuáles son los residuos que se generan en cada uno de ellos, estableciendo los ciclos de generación de residuos. 
      .col-lg-6
        figure.mb-0
          img(src='@/assets/curso/tema8/img2.jpg', alt='Texto que describa la imagen')
    p.mb-4 A continuación, se recomiendan algunos elementos de tipo operativo para el desarrollo de la caracterización: 
    p.mb-4 Consecución de información. Para tal efecto, se recomienda realizar una serie de entrevistas con las personas que hacen parte de la organización, que conozcan su funcionamiento y puedan aportar información sobre el tipo de residuos y las cantidades generadas. 

    TabsA.color-acento-contenido.mb-4
      .tarjeta.colortabs.p-4(titulo="Biosanitarios")
        .row 
          .col-lg-4
            figure.mb-2
              img(src='@/assets/curso/tema3/tab1.png', alt='Texto que describa la imagen')
          .col-lg-8
            p.mb-0 son todos aquellos elementos que tienen contacto con materia orgánica, sangre o fluidos corporales del paciente humano o animal tales como: gasas, apósitos, aplicadores, algodones, drenes, vendajes ropas desechables, toallas higiénicas, pañales entre otros similares (Ministerio del Medio Ambiente, 2002, p.21).
      
      .tarjeta.colortabs.p-4(titulo="Anatomopatológicos")
        .row 
          .col-lg-4
            figure.mb-2
              img(src='@/assets/curso/tema3/tab2.png', alt='Texto que describa la imagen')
          .col-lg-8
            p.mb-0 son los provenientes de restos humanos, muestras para análisis, incluyendo biopsias, tejidos orgánicos amputados, partes y fluidos corporales, que se remueven durante necropsias, cirugías u otros procedimientos, tales como placentas, restos de exhumaciones entre otros. (Ministerio del Medio Ambiente, 2002, p.22)

      .tarjeta.colortabs.p-4(titulo="Cortopunzantes")
        .row 
          .col-lg-4
            figure.mb-2
              img(src='@/assets/curso/tema3/tab3.png', alt='Texto que describa la imagen')
          .col-lg-8
            p.mb-0 son aquellos que por sus características punzantes o cortantes pueden dar origen a un accidente percutáneo infeccioso. Dentro de éstos se encuentran: limas, lancetas, cuchillas, agujas, restos de ampolletas, pipetas, láminas de bisturí o vidrio y cualquier otro elemento que por sus características cortopunzantes pueda lesionar y ocasionar un riesgo infeccioso (Ministerio del Medio Ambiente, 2002, p.22).
      
      .tarjeta.colortabs.p-4(titulo="De animales")
        .row 
          .col-lg-4
            figure.mb-2
              img(src='@/assets/curso/tema3/tab4.png', alt='Texto que describa la imagen')
          .col-lg-8
            p.mb-0 son aquellos provenientes de animales de experimentación, inoculados con microorganismos patógenos y/o los provenientes de animales portadores de enfermedades infectocontagiosas (Ministerio del Medio Ambiente, 2002, p.22).

      .tarjeta.colortabs.p-4(titulo="Radioactivos")
        .row 
          .col-lg-4
            figure.mb-2
              img(src='@/assets/curso/tema3/tab5.png', alt='Texto que describa la imagen')
          .col-lg-8
            p.mb-0 son sustancias emisoras de energía predecible y continua en forma alfa, beta o de fotones, cuya interacción con materia puede dar lugar a rayos X y neutrones. Debe entenderse que estos residuos contienen o están contaminados por radionúclidos en concentraciones o actividades superiores a los niveles de exención establecidos por la autoridad competente para el control del material radiactivo, y para los cuales no se prevé ningún uso (Ministerio del Medio Ambiente, 2002, p.26)


</template>

<script>
export default {
  name: 'Tema8',
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
