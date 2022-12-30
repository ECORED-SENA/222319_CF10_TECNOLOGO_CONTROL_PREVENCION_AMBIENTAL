<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Normativa asociada a los residuos sólidos peligrosos y no peligrosos
    
    .row.align-items-center.mb-4
      .col-lg-6
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-4 
          p.mb-0 En materia ambiental, Colombia cuenta con una de las legislaciones más desarrolladas y mejor concebidas, con una serie de normas que reglamentan cada uno de los aspectos relacionados con la conservación y utilización de los recursos naturales. Muchas de estas normas han surgido para mitigar problemas ambientales experimentados a lo largo del país, pero también han sido formuladas aprovechando la legislación de otras naciones, más avanzadas y su aplicación práctica en el territorio colombiano ha resultado muy compleja o poco eficaz.
        p.mb-4 Actualmente, Colombia cuenta con un amplio desarrollo normativo enmarcado en la Política Nacional para la Gestión de Residuos Sólidos emitida en 1998, actualizada en el CONPES soportada por la Constitución Nacional, la Ley 99 de 1993 y la Ley 142 de 1994, que establece tres objetivos específicos que determinan las prioridades de la gestión en residuos:
        .row 
          .col-lg-12
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-0 Minimizar la cantidad de residuos que se generan.
              li 
                i.fas.fa-check
                p.mb-0 Aumentar el aprovechamiento racional de los residuos sólidos.
              li 
                i.fas.fa-check
                p.mb-0 Mejorar los sistemas de eliminación, tratamiento y disposición final de los residuos sólidos.
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema4/img1.jpg', alt='Texto que describa la imagen')    
    separador

    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 4.1 Leyes expedidas sobre el tema de residuos sólidos y reciclaje

    p.mb-4 En la tabla 2 se presenta una relación general de la normativa de orden nacional aplicable a la cadena asociada a la gestión de los residuos sólidos.
    
    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla 2
                  p Legislación de residuos
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 4.2 Leyes expedidas sobre el tema de residuos sólidos y reciclaje

    p.mb-4 La responsabilidad del generador de los residuos está relacionada a continuación:

    .row.mb-4
      .col-lg-4.col-md-8.col-10
        .row
          .col-12
            .tarjeta.color-primario.p-3
              h4.mb-0 Responsabilidad en residuos peligrosos

    p.mb-4 De acuerdo con el decreto 1076 en el artículo 2.2.6.1.3.1. Obligaciones del Generador. De conformidad con lo establecido en la ley, en el marco de la gestión integral de los residuos o desechos peligrosos, el generador debe:

    .tarjeta.color-opa.p-4.mb-4
      .row.align-items-center.justify-content-center
        .col-lg-8
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span a
              | Garantizar la gestión y manejo integral de los residuos o desechos peligrosos que genera.
            li 
              .lista-ol--cuadro__vineta
                span b
              | Elaborar un plan de gestión integral de los residuos o desechos peligrosos. 
            li 
              .lista-ol--cuadro__vineta
                span c
              | Identificar las características de peligrosidad de cada uno de los residuos o desechos peligrosos que genere.
            li 
              .lista-ol--cuadro__vineta
                span d
              | Garantizar que el envasado o empacado, embalado y etiquetado de sus residuos o desechos peligrosos se realice conforme a la normatividad vigente.
            li 
              .lista-ol--cuadro__vineta
                span e
              | Dar cumplimiento a lo establecido en el Decreto 1609 de 2002 o aquella norma que la modifique o sustituya, cuando remita residuos o desechos peligrosos para ser transportados. 
            li 
              .lista-ol--cuadro__vineta
                span f
              | Registrarse ante la autoridad ambiental competente por una sola vez y mantener actualizada la información de su registro anualmente.
            li 
              .lista-ol--cuadro__vineta
                span g
              | Capacitar al personal encargado de la gestión y el manejo de los residuos o desechos peligrosos en sus instalaciones.
            li 
              .lista-ol--cuadro__vineta
                span h
              | Contar con un plan de contingencia.
            li 
              .lista-ol--cuadro__vineta
                span i
              | Conservar las certificaciones de almacenamiento, aprovechamiento, tratamiento o disposición final que emitan los respectivos receptores, hasta por un tiempo de cinco (5) años.
            li 
              .lista-ol--cuadro__vineta
                span j
              | Tomar todas las medidas de carácter preventivo o de control previas al cese, cierre, clausura o desmantelamiento de su actividad con el fin de evitar cualquier episodio de contaminación que pueda representar un riesgo a la salud y al ambiente, relacionado con sus residuos o desechos peligrosos.
            li 
              .lista-ol--cuadro__vineta
                span k
              | Contratar los servicios de almacenamiento, aprovechamiento, recuperación, tratamiento y/o disposición final, con instalaciones que cuenten con las licencias, permisos y autorizaciones. 
        .col-lg-4.col-md-8.col-8
          figure.mb-2
            img(src='@/assets/curso/tema4/1.png', alt='Texto que describa la imagen')   
    .row.mb-4
      .col-lg-6
        .row
          .col-11
            .tarjeta.color-primario.p-3
              h4.mb-0 Determinación del tipo de generador de residuos peligrosos

    p.mb-4 Se requiere realizar la caracterización de residuos peligrosos para saber su cuantificación, y así determinar si la organización corresponde a alguna de las siguientes categorías establecidas por el Ministerio de Ambiente Vivienda y Desarrollo Territorial mediante el Decreto 1076 de 2015, Artículo 2.2.6.1.1.3. Definiciones.

    figure.mb-5
      .video
        iframe(width="942" height="530" src="https://www.youtube.com/embed/KdqhUWrG08U" title="Información de programa de Tecnología en Prevención y Control Ambiental" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.mb-4
      .col-lg-6.col-md-8.col-10
        .row
          .col-11
            .tarjeta.color-primario.p-3
              h4.mb-0 Prohibiciones de residuos peligrosos

    p.mb-4 De acuerdo con el decreto 1076 Artículo 2.2.6.2.2.1. Prohibiciones, del Ministerio de Ambiente Vivienda y Desarrollo, se prohíbe: 

    figure.mb-5
      .video
        iframe(width="942" height="530" src="https://www.youtube.com/embed/KdqhUWrG08U" title="Información de programa de Tecnología en Prevención y Control Ambiental" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
   
    .row.mb-4
      .col-lg-11
        .row
          .col-11
            .tarjeta.color-primario.p-3
              h4.mb-0 Residuos con obligatoriedad de devolución posconsumo y Residuos de Aparatos Eléctricos y Electrónicos (RAEE).
    p.mb-4 En el 2005, el entonces Ministerio de Ambiente, Vivienda y Desarrollo Territorial (MAVDT) formuló la Política ambiental para la gestión integral de los residuos o desechos peligrosos, que estableció que el manejo inadecuado de los residuos con características de peligrosidad (residuos peligrosos, Respel) y su disposición final junto con residuos no peligrosos, se debía principalmente a la inexistencia de un sistema de manejo separado de los residuos peligrosos.

    figure.mb-4
      img(src='@/assets/curso/tema4/2.png', alt='Texto que describa la imagen')   

    p.mb-4 En este sentido, se establecieron los planes de gestión de devolución de productos posconsumo en Colombia, se identifican los siguientes residuos de posconsumo, con sus respectivos programas:
    .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-4 
      p.mb-0 Medicamentos vencidos, computadores e impresoras en desuso, envases de plaguicidas domésticos, bombillas fluorescentes usadas, baterías usadas plomo acido, pilas usadas, llantas usadas.
    p.mb-4 Así mismo, existen dos programas de devolución posconsumo que actualmente no está por normativa que es devolución posconsumo de celulares y aceites usados.

    .row.mb-4
      .col-lg-4
        .tarjeta.color1.p-4.mb-2
          p.mb-0 <b>Resolución 1511 de 2010,</b> Ministerio de Ambiente, Vivienda y Desarrollo Territorial, “por la cual se establecen los sistemas de recolección selectiva y gestión ambiental de residuos de bombillas y se adoptan otras disposiciones”.
      .col-lg-4
        .tarjeta.color1.p-4.mb-2
          p.mb-0 <b>Resolución 1512 de 2010,</b> Ministerio de Ambiente, Vivienda y Desarrollo Territorial, “por la cual se establecen los sistemas de recolección selectiva y gestión ambiental de residuos de bombillas y se adoptan otras disposiciones”.
      .col-lg-4
        .tarjeta.color1.p-4.mb-2
          p.mb-0 <b>Resolución 1297 de 2010,</b> Ministerio de Medio Ambiente, Vivienda y Desarrollo Territorial, “por la cual se establecen los sistemas de recolección selectiva y gestión ambiental de residuos de pilas y acumuladores y se adoptan otras disposiciones”.

    p.mb-4 La ley también estipula que los RAEE son residuos de manejo diferenciado y prohíbe su disposición final en rellenos sanitarios, para que sean recolectados y gestionados por los productores y para priorizar su aprovechamiento mediante empresas gestoras que cuenten con licencia ambiental para ello, ver figura 4. 

    .row.mb-2
      .col-lg-8
        .tarjeta.color-verde.p-4.mb-2
          .row
            .col-lg-4.col-md-4.col-6
              h4.text-center.mb-4 Electrodomésticos
              figure.mb-2
                img(src='@/assets/curso/tema4/icon1.png', alt='Texto que describa la imagen') 
              h4.text-center.mb-4 Equipos de iluminación
              figure.mb-2
                img(src='@/assets/curso/tema4/icon4.png', alt='Texto que describa la imagen')   
            .col-lg-4.col-md-4.col-6
              h4.text-center.mb-4 Electrónica de consumo y TIC
              figure.mb-2
                img(src='@/assets/curso/tema4/icon2.png', alt='Texto que describa la imagen') 
              h4.text-center.mb-4 Juguetes eléctricos o electrónicos
              figure.mb-2
                img(src='@/assets/curso/tema4/icon5.png', alt='Texto que describa la imagen')  
            .col-lg-4.col-md-4.col-6
              h4.text-center.mb-4 Herramientas Eléctricas
              figure.mb-2
                img(src='@/assets/curso/tema4/icon3.png', alt='Texto que describa la imagen') 
              h4.text-center.mb-4 Pilas y acumuladores
              figure.mb-2
                img(src='@/assets/curso/tema4/icon6.png', alt='Texto que describa la imagen') 
        .tarjeta.color-verde2.p-2.mb-4
          p.mb-0.text-center <b>AEE de consumo masivo o domésticos</b>
        .tarjeta.color-amarillo.p-4.mb-0
          .row
            .col-lg-4.col-md-4.col-6
              h4.text-center.mb-4 Equipos Eléctricos
              figure.mb-2
                img(src='@/assets/curso/tema4/icon7.png', alt='Texto que describa la imagen') 
            .col-lg-4.col-md-4.col-6
              h4.text-center.mb-4 Maquinaria y herramientas eléctricas
              figure.mb-2
                img(src='@/assets/curso/tema4/icon8.png', alt='Texto que describa la imagen') 
            .col-lg-4.col-md-4.col-6
              h4.text-center.mb-4 Dispositivos Electromédicos
              figure.mb-2
                img(src='@/assets/curso/tema4/icon9.png', alt='Texto que describa la imagen') 
          .row.justify-content-center
            .col-lg-5.col-md-4.col-6
              h4.text-center.mb-4 Instrumentos de vigilancia y control
              figure.mb-2
                img(src='@/assets/curso/tema4/icon10.png', alt='Texto que describa la imagen') 
            .col-lg-5.col-md-4.col-6
              h4.text-center.mb-4 Máquinas expendedoras
              figure.mb-2
                img(src='@/assets/curso/tema4/icon11.png', alt='Texto que describa la imagen') 
        .tarjeta.color-amarillo2.p-2.mb-4
          p.mb-0.text-center <b>AEE de consumo masivo o domésticos</b>
      .col-lg-4
        .tarjeta.color-cian.p-5
          p.mb-4 <b>Línea blanca:</b> Incluye los electrodomésticos que sirven para la cocina, el lavado, la refrigeración y ventilación.
          p.mb-4 <b>Línea marrón:</b> Comprende una parte de la electrónica de consumo que engloba todos los equipos electrónicos utilizados cotidianamente para el entrenamiento, las comunicaciones y la oficina. En esta categoría se encuentran: televisores, equipos reproductores y grabadores de sonido y de video.
          p.mb-4 <b>Línea gris:</b> Hace referencia a los equipos y aparatos de la gama de las tecnologías de la información y de las comunicaciones (TIC) e incluye los computadores, impresoras, copiadoras, celulares y periféricos.
          p.mb-4 <b>Pequeños electrodomésticos:</b> Pertenecen a esta línea los electrodomésticos menores que son utilizados en las cocinas, además de otros que se usan para el cuidado personal.
    figcaption.mb-4 Nota. Política Nacional integral de residuos de aparatos electrónicos, Minambiente (2017). 

    .row.mb-4
      .col-lg-6
        .row
          .col-11
            .tarjeta.color-primario.p-3
              h4.mb-0 Requerimientos de residuos sólidos para el aprovechamiento.

    p.mb-4 Según el decreto 1077 de 2015 en el Artículo 2.3.2.2.2.8.82, Requerimientos de los residuos sólidos para el aprovechamiento, en las actividades de aprovechamiento, los residuos deben cumplir por lo menos con los siguientes criterios básicos y requerimientos, para que los métodos de aprovechamiento se realicen en forma óptima: 

    .row.justify-content-center.mb-4
      .col-lg-12
        .row.justify-content-center
          .col-lg-5.col-md-6.col-8.mb-4
            .tarjeta.tarjeta-slide.arriba.fondoimg(@mouseover="indicadorTarjetaSlide = false")
              .indicador--hover(v-if="indicadorTarjetaSlide")
              .tarjeta-slide__contenedor
                .tarjeta-slide__contenido.px-4.py-4
                  p.mb-0 Los residuos sólidos deben estar debidamente separados por tipo de material, de acuerdo con los lineamientos establecidos en el Plan de Gestión Integral de Residuos Sólidos (PGIRS) o en su defecto sujetándose a lo establecido en el programa de prestación por la persona prestadora de la actividad de aprovechamiento. 
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema4/3.png')})`}")
          .col-lg-5.col-md-6.col-8
            .tarjeta.tarjeta-slide.arriba.fondoimg2(@mouseover="indicadorTarjetaSlide = false")
              .indicador--hover(v-if="indicadorTarjetaSlide")
              .tarjeta-slide__contenedor
                .tarjeta-slide__contenido.px-4.py-4
                  p.mb-0 No deben estar contaminados con residuos peligrosos, metales pesados, ni bifenilos policlorados. 
                .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema4/5.png')})`}")
    p.mb-4 En el caso de las fracciones de residuos sólidos orgánicos biodegradables, el almacenamiento temporal no puede superar las cuarenta y ocho (48) horas.
    separador

    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 4.3 Residuos especiales

    p.mb-4 Son aquellos residuos que por su naturaleza, composición, tamaño, volumen y peso no puedan ser recolectados, manejados, tratados o dispuestos normalmente por la persona prestadora del servicio. Incluye los residuos producto de las actividades de corte de césped y poda de árboles ubicados en las vías y áreas públicas; aquellos provenientes del barrido y limpieza de vías y áreas públicas, y los residuos provenientes de actividades de construcción y demás obras civiles. (Área metropolitana del valle de aburra, 2016, p.8). Algunos ejemplos de residuos especiales son: llantas usadas, ropa, colchones, muebles, escombros, lodos, camas, algunos RAEES como las antenas de telecomunicaciones por su voluminosidad.

    figure.mb-4
      img(src='@/assets/curso/tema4/7.png', alt='Texto que describa la imagen')

    .row.mb-4
      .col-lg-6
        .row
          .col-11
            .tarjeta.color-primario.p-3
              h4.mb-0 Residuos de Construcción y Demolición (RCD)
    p.mb-4 Si la organización genera algún tipo de actividad como remodelación, construcción o demolición requiere realizar el trámite con la autoridad ambiental por la generación de este tipo de residuos RCD, se enuncia lo más destacado de la norma. De acuerdo con la resolución 472 de 2017 Por la cual se reglamenta la gestión integral de los residuos generados en las actividades de Construcción y Demolición (RCD) y se dictan otras disposiciones en el artículo 2 se debe tener en cuenta las siguientes definiciones:

    .row.mb-4
      .col-lg-11 
        figure.desaparece
          img(src='@/assets/curso/tema4/fig1.svg', alt='Texto que describa la imagen')

    .row.mb-4
      .col-lg-12
        figure.desaparece2
          img(src='@/assets/curso/tema4/fig2.svg', alt='Texto que describa la imagen')

    .row.mb-4
      .col-lg-3
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Obligaciones. 

    p.mb-4 En el artículo 15 menciona:
    p.mb-4 Artículo 15. Obligaciones de los generadores de RCD. Son obligaciones de los generadores de RCD las siguientes:

    ul.lista-ul--color
      li 
        i.fas.fa-check
        p.mb-0 Los grandes generadores deberán formular, implementar y mantener actualizado el Programa de Manejo Ambiental de RCD que se especifica en la norma.
      li 
        i.fas.fa-check
        p.mb-0 Los pequeños generadores tienen la obligación de entregar los RCD a un gestor de RCD para que se realicen las actividades de recolección y transporte hasta los puntos limpios, sitios de aprovechamiento o disposición final según sea el caso.
      
    p.mb-4 Para profundizar en el tema se invita a consultar la siguiente información:
    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Matriz de requisitos legales
                  p En el material complementario revise la Matriz de requisitos legales del año 2020
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


</template>

<script>
export default {
  name: 'Tema4',
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
