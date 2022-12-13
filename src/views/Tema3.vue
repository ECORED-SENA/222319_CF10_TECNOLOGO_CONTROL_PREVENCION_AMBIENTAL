<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Conceptos generales

    .row.justify-content-center.mb-4
      .col-lg-10
        p.mb-4 Según la literatura sobre el tema para identificar los diferentes tipos de residuos, se pueden clasificar según cuatro criterios principales:
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema3/fig1.svg', alt='Texto que describa la imagen')

          .tarjeta.color-amarillo.p-3(x="9.6%" y="57.5%" numero="")
            p <b>Clasificación de los residuos según grado de peligrosidad:</b> Se clasifican en residuos peligrosos y no peligrosos esto quiere decir según el grado de peligrosidad al medio ambiente o a la salud humana.

          .tarjeta.color-amarillo.p-3(x="26.7%" y="90.5%" numero="")
            p <b>Clasificación de los residuos según su origen:</b> Esto quiere decir si son de origen doméstico proveniente de los hogares, origen comercial si son propias del comercio, industrial si son del sector industrial, de escombros y residuos de construcción del sector de construcción, residuos sanitarios si son de centros y establecimientos sanitarios, residuos mineros si son de minas, residuos agrícolas si son del sector agrícola. 

          .tarjeta.color-amarillo.p-3(x="50.4%" y="100%" numero="")
            p <b>Clasificación de los residuos según su aprovechamiento:</b> Se clasifican en aprovechables y no aprovechables, esto depende de cada caso en particular del residuo que se esté tratando y su estado (calidad del residuo).

          .tarjeta.color-amarillo.p-3(x="73.5%" y="90.5%" numero="")
            p <b>Clasificación de los residuos según su biodegradabilidad:</b> Quiere decir si es orgánico o inorgánico.

          .tarjeta.color-amarillo.p-3(x="90.5%" y="58.5%" numero="")
            p <b>Clasificación según su composición:</b> Clasificación según tipos de materiales o componentes químicos de lo que esté hecho.
    separador

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 3.1 Clasificación y características de los residuos

    p.mb-4 Los residuos son resultado de actividades domésticas, comerciales, industriales, institucionales, de prestación de servicios, entre otras. 

    .row.mb-4
      .col-lg-3
        .row
          .col-9
            .tarjeta.color-primario.p-3
              h4.mb-0 Residuos Peligrosos

    p.mb-4 En la figura 2 se presenta el esquema que facilita la identificación de los residuos o desechos peligrosos, basados en la normatividad ambiental vigente que tiene en cuenta la mayoría de los criterios de peligrosidad establecidos en el convenio de Basilea, del cual Colombia es signataria desde al año 1995, mediante la Ley 253. Dicho convenio fue ratificado el 31 de diciembre de 1996 y entró en vigencia para Colombia desde marzo 31 de 1997.

    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 2
          span Tabla criterios de peligrosidad.
        figure.mb-2
          img(src='@/assets/curso/tema3/fig2.svg', alt='Texto que describa la imagen')
        figcaption Nota. Manual para el manejo integral de residuos sólidos en el valle de aburra. Área metropolitana del valle de aburra (2016). 
    .row.justify-content-center.mb-4
      .col-lg-12
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4
          p.mb-0 A esta gráfica se le conoce con la sigla de CRETIIR usada para relacionar las características que un residuo peligroso pueda tener, cada letra significa: (C: Corrosivo, R: Radioactivo, E: Explosivo, T: Tóxico, I: Inflamable, I: Infeccioso, R: Radioactivo)

    .row.align-items-center.mb-2
      .col-lg-7
        .row.mb-4
          .col-lg-3
            .tarjeta.color-verde.p-2.mb-4
              h4.mb-0.text-center Corrosivo
          .col-lg-12
            p.mb-0 Los residuos que se consideran como peligrosos en función de su corrosividad son aquellos muy ácidos (pH < 2.0) o muy alcalinos (pH > 12.5) que pueden reaccionar peligrosamente con otros residuos o provocar la migración de contaminantes tóxicos, o bien que son capaces de corroer el acero en ciertas condiciones y en cierto tiempo, con lo cual pueden llegar a fugarse de sus contenedores y liberar otros residuos (Instituto Nacional de Tecnología y Cambio Climático, 2007).
        .row
          .col-lg-3
            .tarjeta.color-verde.p-2.mb-4
              h4.mb-0.text-center Reactivo
          .col-lg-12
            p.mb-0 Los residuos reactivos son aquellos que son normalmente inestables y pueden llegar a reaccionar violentamente sin explosión; que pueden formar una mezcla explosiva con el agua, generar gases tóxicos, vapores y humos; que pueden contener cianuro o sulfuro y generar gases tóxicos; o bien que pueden ocasionar explosiones en distintas situaciones, ya sea de temperatura y presión estándares, si se calientan en condiciones de confinamiento o se someten a fuerzas considerables (Instituto Nacional de Tecnología y Cambio Climático, 2007).
      .col-lg-5
        figure.mb-2
          img(src='@/assets/curso/tema3/1.png', alt='Texto que describa la imagen')
    
    .row.align-items-center.mb-2
      .col-lg-7
        .row.mb-4
          .col-lg-3
            .tarjeta.color-verde.p-2.mb-4
              h4.mb-0.text-center Explosivo
          .col-lg-12
            p.mb-0 Los residuos explosivos son aquellos que tienen una constante de explosividad igual o mayor a la del dinitrobenceno, o bien que son capaces de producir una reacción o descomposición detonante o explosiva a 25ºC y a 1.03 kg/cm2 de presión (Instituto Nacional de Tecnología y Cambio Climático, 2007).
        .row
          .col-lg-3
            .tarjeta.color-verde.p-2.mb-4
              h4.mb-0.text-center Tóxicos
          .col-lg-12
            p.mb-0 Los residuos tóxicos son los que contienen sustancias capaces de causar la muerte o provocar efectos nocivos en la salud de la población, en la flora o en la fauna, que varían en características y severidad de acuerdo con las formas e intensidades de la exposición (Instituto Nacional de Tecnología y Cambio Climático, 2007).
            p.mb-4 Para este efecto se consideran tóxicos los residuos o desechos que se clasifican de acuerdo con los criterios de toxicidad (efectos agudos, retardados o crónicos y ecotóxicos) definidos a continuación y para los cuales, según sea necesario, las autoridades competentes establecerán los límites de control correspondiente:
            ol.lista-ol--cuadro
              li 
                .lista-ol--cuadro__vineta
                  span a
                | Dosis Letal media oral (DL50) para ratas menor o igual a 200 mg/kg para sólidos y menor o igual a 500 mg/kg para líquidos, de peso corporal.
              li 
                .lista-ol--cuadro__vineta
                  span b
                | Dosis Letal media dérmica (DL50) para ratas menor o igual de 1.000 mg/kg de peso corporal.
              li 
                .lista-ol--cuadro__vineta
                  span c
                | Concentración Letal media inhalatoria (CL50) para ratas menor o igual a 10 mg/l.
              li 
                .lista-ol--cuadro__vineta
                  span d
                | Alto potencial de irritación ocular, respiratoria y cutánea, capacidad corrosiva sobre tejidos vivos.
              li 
                .lista-ol--cuadro__vineta
                  span e
                | Susceptibilidad de bioacumulación y biomagnificación en los seres vivos y en las cadenas tróficas.
              li 
                .lista-ol--cuadro__vineta
                  span f
                | Carcinogenicidad, mutagenicidad y teratogenecidad.
              li 
                .lista-ol--cuadro__vineta
                  span g
                | Neurotoxicidad, inmunotoxicidad u otros efectos retardados.
              li 
                .lista-ol--cuadro__vineta
                  span h
                | Toxicidad para organismos superiores y microorganismos terrestres y acuáticos.
              li 
                .lista-ol--cuadro__vineta
                  span i
                | Otros que las autoridades competentes definan como criterios de riesgo de toxicidad humana o para el ambiente.
      .col-lg-5
        figure.mb-2
          img(src='@/assets/curso/tema3/2.png', alt='Texto que describa la imagen')
    p.mb-4 Además, se considera residuo o desecho tóxico aquel que, al realizársele una prueba de lixiviación para característica de toxicidad (conocida como prueba TCLP), contiene uno o más de las sustancias, elementos o compuestos que se presentan en la tabla 1 en concentraciones superiores a los niveles máximos permisibles en el lixiviado establecidos en dicha tabla.

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla 1
                  p Concentraciones máximas de contaminantes para la prueba TCLP
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    .row.align-items-center.mb-4
      .col-lg-7
        .row.mb-4
          .col-lg-3
            .tarjeta.color-verde.p-2.mb-4
              h4.mb-0.text-center Inflamable
          .col-lg-12
            p.mb-0 Los residuos inflamables son aquellos capaces de causar un incendio en diferentes condiciones tales como fricción, absorción de humedad, cambios químicos espontáneos, y que al incendiarse arden tan vigorosa y persistentemente que pueden representar un riesgo (Instituto Nacional de Tecnología y Cambio Climático, 2007).
        .row
          .col-lg-3
            .tarjeta.color-verde.p-2.mb-4
              h4.mb-0.text-center Infeccioso
          .col-lg-12
            p.mb-0 A los residuos infecciosos se les conoce también como residuos biológicos o patógenos. Son aquellos que contienen microorganismos patógenos tales como bacterias, parásitos, virus, hongos, virus oncogénicos y recombinantes como sus toxinas, con el suficiente grado de virulencia y concentración que pueda producir una enfermedad infecciosa en huéspedes susceptibles (Ministerio del Medio Ambiente, 2002, p.20).
      .col-lg-5
        figure.mb-2
          img(src='@/assets/curso/tema3/3.png', alt='Texto que describa la imagen')

    p.mb-4 Los residuos infecciosos o de riesgo biológico se clasifican en:

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

    .row.mb-4
      .col-lg-3
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Residuos no peligrosos

    .row.align-items-center.mb-4
      .col-lg-6
        p.mb-2 Los residuos no peligrosos se clasifican en: 
        LineaTiempoD.color-acento-contenido
          p(numero="1" titulo="Biodegradables") son aquellos restos químicos o naturales que se descomponen fácilmente en el ambiente. En estos restos se encuentran los vegetales, residuos alimenticios no infectados, papel higiénico, papeles no aptos para reciclaje, jabones y detergentes biodegradables, madera y otros residuos que puedan ser transformados fácilmente en materia orgánica (Ministerio del Medio Ambiente, 2002, p.18).
          
          p(numero="2" titulo="Reciclables") son aquellos que no se descomponen fácilmente y pueden volver a ser utilizados en procesos productivos como materia prima. Entre estos residuos se encuentran: algunos papeles y plásticos, chatarra, vidrio, telas, radiografías, partes y equipos obsoletos o en desuso, entre otros (Ministerio del Medio Ambiente, 2002, p.19).
          
          p(numero="3" titulo="Inertes") son aquellos que no se descomponen ni se transforman en materia prima y su degradación natural requiere grandes períodos de tiempo. Entre estos se encuentran: el icopor, algunos tipos de papel como el papel carbón y algunos plásticos (Ministerio del Medio Ambiente, 2002, p.19).
          
          p(numero="4" titulo="Ordinarios o comunes") son aquellos generados en el desempeño normal de las actividades. Estos residuos se generan en oficinas, pasillos, áreas comunes, cafeterías, salas de espera, auditorios y en general en todos los sitios del establecimiento del generador (Ministerio del Medio Ambiente, 2002, p.19).

      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema3/4.png', alt='Texto que describa la imagen')

    .row.mb-4
      .col-lg-3
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Residuos especiales

    p.mb-4 Según el tipo este residuo puede ser no peligroso o peligroso, ver figura 3; un residuo especial requiere de un manejo especial sea por su naturaleza, composición, tamaño, volumen y peso no puedan ser recolectados, manejados, tratados o dispuestos normalmente por la persona prestadora del servicio. Incluye los residuos producto de las actividades de corte de césped y poda de árboles ubicados en las vías y áreas públicas; aquellos provenientes del barrido y limpieza de vías y áreas públicas, y los residuos provenientes de actividades de construcción y demás obras civiles (Área metropolitana del valle de aburra, 2016, p.8).

    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 3
          span  Clasificación de los residuos sólidos
        figure.mb-2
          img(src='@/assets/curso/tema3/fig3.svg', alt='Texto que describa la imagen')
        figcaption Nota. Clasificación de residuos sólidos, SENA (2020).

</template>

<script>
export default {
  name: 'Tema3',
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
