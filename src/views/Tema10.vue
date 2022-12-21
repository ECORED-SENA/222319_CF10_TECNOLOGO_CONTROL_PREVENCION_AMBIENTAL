<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 10
      h1 Reconocimiento del sitio de almacenamiento temporal y/o final de los residuos

    figure.mb-4
      img(src='@/assets/curso/tema10/1.png', alt='Texto que describa la imagen')

    p.mb-4 Se recomienda establecer la existencia y ubicación de los sitios de almacenamiento dentro de la organización, evaluando las características que debe cumplir como, ver tabla 8:

    .titulo-sexto.color-acento-contenido.mb-2
      h5 Tabla 8      
      span Características de los sitios de almacenamiento de residuos no peligrosos
    .tabla-a.color-acento-botones.mb-5 
      table
        caption Nota. Área metropolitana del valle de aburra (2016). 
        thead
          tr
            th(style='background-color: #DFF2ED').anch DESCRIPCIÓN
            th(style='background-color: #DFF2ED') CUMPLE
            th(style='background-color: #DFF2ED') NO CUMPLE
          tr(style='background-color: #FFFFFF')
            td 1. Localizado al interior de la organización y de acceso restringido.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 2. Los acabados permiten su limpieza e impiden la formación de ambientes propicios para el desarrollo de microorganismos.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 3. Cubierto para protección de aguas lluvias, Iluminación y ventilación adecuada (rejillas o ventanas), sistema de drenaje y piso duro e impermeable
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 4. Posee sistemas de control de incendios (equipo de extinción de incendios, suministro cercano de agua, etc.)
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 5. La unidad de almacenamiento evita el acceso y proliferación de animales domésticos, roedores y otras clases de vectores.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 6. El sitio no causa molestias e impactos a la comunidad.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 7. Cuenta con recipientes o cajas de almacenamiento para realizar su adecuada presentación.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 8. La unidad de almacenamiento es aseada, fumigada y desinfectada frecuentemente.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 9. Dispone en lo posible de una báscula o sistema de medición de pesos o volúmenes y se lleva un registro para el control de la generación de residuos.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 10. Debe ser de uso exclusivo para almacenar residuos y estar debidamente señalizado.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 11. Disponer de espacios por clase de residuo, de acuerdo a su clasificación (reciclable, peligroso, ordinario, etc.).
            td
            td 
    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla_8
                  p Características de los sitios de almacenamiento de residuos no peligrosos.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    p.mb-4 A continuación, se definen las características mínimas de los sitios de almacenamiento de residuos o desechos peligrosos, ver tabla 9:

    .titulo-sexto.color-acento-contenido.mb-2
      h5 Tabla 9    
      span Características mínimas de los sitios de almacenamiento de residuos peligrosos.
    .tabla-a.color-acento-botones.mb-5 
      table
        caption Nota. Área metropolitana del valle de aburra (2016).
        thead
          tr
            th(style='background-color: #DFF2ED').anch DESCRIPCIÓN
            th(style='background-color: #DFF2ED') CUMPLE
            th(style='background-color: #DFF2ED') NO CUMPLE
          tr(style='background-color: #FFFFFF')
            td 1. La bodega está alejada de zonas densamente pobladas, de fuentes de captación de agua potable, de áreas inundables y de posibles fuentes externas de peligro.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 2. La bodega está ubicada en un sitio de fácil acceso para el transporte y para situaciones de emergencia.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 3. En caso de contar con salida de emergencia, ésta debe estar señalizada.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 4. El piso es no resbaloso, impermeable, libre de grietas y resistente a las sustancias y/o residuos que se almacenen.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 5. Los drenajes del interior de la bodega están conectados a pozos colectores para una posterior disposición del agua residual.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 6. Los drenajes están sellados y protegidos de daño por el paso de vehículos y el movimiento de estibas.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 7. Todas las sustancias peligrosas almacenadas están ubicadas en un sitio confinado mediante paredes, diques o bordillos perimetrales.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 8. El techo está diseñado de tal forma que no admita el ingreso de agua lluvia a las instalaciones.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 9. La bodega cuenta con ventilación adecuada (ya sea natural o forzada).
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 10. La bodega opera con iluminación adecuada.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 11. Están señalizadas todas las áreas de almacenamiento y estanterías con la clase de riesgo correspondiente a la sustancia química peligrosa almacenada.
            td
            td 
          tr(style='background-color: #FFFFFF')
            td 12. Están señalizados todos los lugares de almacenamiento con las correspondientes señales de advertencia, obligación, prohibición e información.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 13. Cuenta con sistemas de control de incendios como equipos de extinción y suministro cercano de agua.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 14. Posee las Hojas de Seguridad de todas las sustancias almacenadas, y se encuentran en un lugar visible y señalizado.
            td
            td 
    
    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla_9
                  p Características mínimas de los sitios de almacenamiento de residuos peligrosos.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    p.mb-4 Adicionalmente es necesario evaluar actividades inherentes al almacenamiento, tabla 10: 
    .titulo-sexto.color-acento-contenido.mb-2
      h5 Tabla 10  
      span Actividades inherentes al almacenamiento de residuos peligrosos.
    .tabla-a.color-acento-botones.mb-5 
      table
        caption Nota. Área metropolitana del valle de aburra (2016).
        thead
          tr
            th(style='background-color: #DFF2ED').anch DESCRIPCIÓN
            th(style='background-color: #DFF2ED') CUMPLE
            th(style='background-color: #DFF2ED') NO CUMPLE
          tr(style='background-color: #FFFFFF')
            td 1. Están definidas y documentadas las responsabilidades de cada actor asociado a la operación de almacenamiento.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 2. El proveedor y/o dueño de las sustancias químicas peligrosas provee las Hojas de Seguridad.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 3. Asegura que todas las sustancias peligrosas almacenadas estén debidamente etiquetadas o marcadas.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 4. Cuenta con un registro actual de las sustancias químicas peligrosas almacenadas que garantice el conocimiento de la cantidad y ubicación de las sustancias.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 5. La bodega de almacenamiento se mantiene limpia y ordenada.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 6. Organizan regularmente inspecciones ambientales y de seguridad.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 7. Almacenan las sustancias químicas peligrosas agrupando las que tienen riesgos comunes y evitando la proximidad de las incompatibles.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 8. Ha dejado un pasillo peatonal perimetral entre los materiales almacenados y los muros.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 9. El apilamiento de recipientes y bultos es menor a tres metros de altura.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 10. Los estantes son suficientemente estables y firmes, de forma que no exista el riesgo de derrumbamiento del mismo.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 11. Los estantes son de un material resistente a las sustancias almacenadas.
            td
            td 
          tr(style='background-color: #FFFFFF')
            td 12. Las sustancias peligrosas o residuos almacenados tienen las debidas protecciones para evitar caídas y derrames.
            td 
            td 
          tr(style='background-color: #FFFFFF')
            td 13. Tiene en cuenta las recomendaciones de las Hojas de Seguridad para la ubicación de las sustancias peligrosas dentro de la bodega.
            td 
            td 
    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla_10 
                  p Actividades inherentes al almacenamiento de residuos peligrosos.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    p.mb-4 Los Almacenamiento de residuos la mayoría de las veces se divide en bodegas una bodega de almacenamiento para residuos no peligrosos ordinarios, otra bodega de almacenamiento de residuos reciclables y otra bodega de residuos peligrosos, o se comparte la bodega colocando divisiones, para el caso de residuos peligrosos se debe tener en cuenta la matriz de compatibilidad de los residuos

</template>

<script>
export default {
  name: 'Tema10',
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
