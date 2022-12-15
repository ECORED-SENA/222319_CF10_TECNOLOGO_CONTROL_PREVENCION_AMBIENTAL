<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Identificación de los recipientes, puntos de generación de residuos y ECOMAPA

    figure.mb-4
      img(src='@/assets/curso/tema7/1.png', alt='Texto que describa la imagen') 
    p.mb-4 Se debe establecer la composición, cantidad, características y calidad de los residuos especiales, peligrosos y no peligrosos que se generan en la organización, por medio de una caracterización y aforo de acuerdo con alguna de las metodologías existentes para este fin.   
    separador

    #t_7_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 7.1 Leyes expedidas sobre el tema de residuos sólidos y reciclaje

    p.mb-4 Mediante la siguiente tabla 3 se tendrá noción de los residuos que comúnmente se generan y se orienta sobre qué se puede hacer con ellos.

    .row.justify-content-center
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Tabla 3
          span Tipos de residuos
        figure.mb-2
          img(src='@/assets/curso/tema7/tabla.svg', alt='Texto que describa la imagen')
        figcaption Nota. Gestión Ambiental Residuos sólidos Guía para la separación en la fuente.  ICONTEC (2009).
    separador

    #t_7_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 7.2 Identificación de actividades de minimización de residuos

    p.mb-4 Para dar respuesta a la pirámide de jerarquización de la gestión de residuos, es importante identificar en el diagnóstico qué prácticas y actividades aportan a la prevención y minimización de residuos en la organización, se debe tener en cuenta la siguiente información:

    .row.mb-4
      .col-lg-6
        .tarjeta.color-verde4.p-3
          .row.align-items-center
            .col-lg-2
              figure.mb-2
                img(src='@/assets/curso/tema7/icon1.png', alt='Texto que describa la imagen')
            .col-lg-10
              p.mb-0 La adopción de buenas prácticas, la optimización de los procesos, el cambio a tecnologías limpias, la sustitución de materias primas y la modificación de productos. 

      .col-lg-6
        .tarjeta.color-verde4.p-3
          .row.align-items-center
            .col-lg-2
              figure.mb-2
                img(src='@/assets/curso/tema7/icon2.png', alt='Texto que describa la imagen')
            .col-lg-10
              p.mb-0 La reutilización de elementos que se generan en los procesos de la organización. 

    .row.mb-4
      .col-lg-6
        .tarjeta.color-verde4.p-3
          .row.align-items-center
            .col-lg-2
              figure.mb-2
                img(src='@/assets/curso/tema7/icon3.png', alt='Texto que describa la imagen')
            .col-lg-10
              p.mb-0 Igualmente, el reciclaje de materiales, aprovechamiento de subproductos utilizándolos como materias primas dentro del mismo proceso productivo o dentro de otro.    

      .col-lg-6
        .tarjeta.color-verde4.p-3
          .row.align-items-center
            .col-lg-2
              figure.mb-2
                img(src='@/assets/curso/tema7/icon4.png', alt='Texto que describa la imagen')
            .col-lg-10
              p.mb-0 La utilización de una menor cantidad de empaques, solicitando al proveedor la entrega de productos sin envolturas innecesarias, el empleo de elementos que sean susceptibles de aprovechamiento para reemplazar el uso de aquellos que no lo son.
    separador

    #t_7_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 7.3 Separación en la fuente

    p.mb-4 Se debe determinar si en la organización se realiza separación en la fuente, si es así, tener en cuenta aspectos como: 

    .row.justify-content-center.mb-4
      .col-lg-10
        .row.mb-4 
          .col-lg-6
            .tarjeta.color-amarillo3.p-3
              .row.align-items-center
                .col-lg-2
                  figure.mb-2
                    img(src='@/assets/curso/tema7/icon5.png', alt='Texto que describa la imagen')
                .col-lg-10
                  p.mb-0 Tipo de residuos que se separan. 
          .col-lg-6
            .tarjeta.color-amarillo3.p-3
              .row.align-items-center
                .col-lg-2
                  figure.mb-2
                    img(src='@/assets/curso/tema7/icon5.png', alt='Texto que describa la imagen')
                .col-lg-10
                  p.mb-0 Existencia y cantidad de recipientes adecuados (capacidad, código de colores, entre otros). 
          
        .row 
          .col-lg-6
            .tarjeta.color-amarillo3.p-3
              .row.align-items-center
                .col-lg-2
                  figure.mb-2
                    img(src='@/assets/curso/tema7/icon5.png', alt='Texto que describa la imagen')
                .col-lg-10
                  p.mb-0 Ubicación estratégica dentro de la organización y distribución por zonas. 
          .col-lg-6
            .tarjeta.color-amarillo3.p-3
              .row.align-items-center
                .col-lg-2
                  figure.mb-2
                    img(src='@/assets/curso/tema7/icon5.png', alt='Texto que describa la imagen')
                .col-lg-10
                  p.mb-0 Calidad de la separación.  
    .row.mb-4
      .col-lg-4
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Identificación de recipientes 

    .row.align-items-center.mb-4 
      .col-lg-6
        p.mb-4 La separación en la fuente es la base fundamental de la adecuada gestión de residuos y consiste en la separación inicial de manera selectiva de los residuos procedentes de cada uno de los centros generadores de la organización, iniciándose una cadena de actividades y procesos cuya efectividad depende de la adecuada clasificación de los residuos.  
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-0
          p.mb-4 El diagnóstico permite definir el tipo y cantidad de recipientes que se requieren para la adecuada separación de los residuos en todas las áreas de la organización. Los recipientes utilizados preferiblemente deben cumplir con el color correspondiente a la clase de residuos que se va a depositar en ellos y que se denomina Código de Colores. Además, deben ser visibles y estar ubicados estratégicamente en las instalaciones de la organización; en caso de que los recipientes que posee la organización no cumplan con el Código de Colores pueden pintarse, emplear cintas adhesivas visibles o utilizar el fondo del rótulo para establecer el color correspondiente al tipo de residuo mientras realiza la correspondiente compra del recipiente. 
          p.mb-0 Para cumplir con el Código de Colores no se requiere de bolsas del mismo color del recipiente, estas pueden ser reemplazadas por bolsas transparentes o de color, teniendo cuidado en el momento de recolección selectiva de cada residuo. 
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema7/1.jpg', alt='Texto que describa la imagen')

    .row.justify-content-center.mb-4
      .col-lg-10
        p.mb-4 Para conocer más sobre el tema se puede visualizar el siguiente video: 
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema7/icon6.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  p <b>En el material complementario revise el video “Conoce la nueva resolución para separar los residuos en Colombia”</b>
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    p.mb-4 A partir del 1 de enero de 2021, los municipios y distritos deberán implementar el código de colores para la presentación de los residuos sólidos en bolsas u otros recipientes, en el marco de los programas de aprovechamiento de residuos del servicio público de aseo, de acuerdo con lo establecido en los Planes de Gestión Integral de Residuos Sólidos (PGIRS).

    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 6
          span Código de colores obligatorio a partir del año 2021 para entregar al servicio público de aseo en todo el territorio nacional
        .tarjeta.color-cuadro.p-2
          .row.mb-4
            .col-lg-3
              figure.mb-2
                img(src='@/assets/curso/tema7/logo.png', alt='Texto que describa la imagen')
            .col-lg-4
              span
            .col-lg-5.tex
              p.mb-0 código de colores para la
              <b>SEPARACIÓN DE RESIDUOS A NIVEL NACIONAL</b>
          .row.mb-2
            .col-lg-4
              figure.mb-2
                img(src='@/assets/curso/tema7/basura1.png', alt='Texto que describa la imagen')
            .col-lg-4
              figure.mb-2
                img(src='@/assets/curso/tema7/basura2.png', alt='Texto que describa la imagen')
            .col-lg-4
              figure.mb-2
                img(src='@/assets/curso/tema7/basura3.png', alt='Texto que describa la imagen')
        figcaption Nota. Gobierno unifica el código de colores para la separación de residuos en la fuente a nivel nacional. Ministerio de Ambiente (2020).  
    p.mb-4 Esta norma es obligatoria a nivel nacional para los residuos que se entreguen al servicio de aseo, este código de colores deberá ser adoptado por los municipios o distritos que adelanten programas de aprovechamiento conforme a sus Planes de Gestión Integral de Residuos Sólidos (PGIRS) y permitirá simplificar la separación en la fuente en los hogares, preparando al país para el desarrollo e implementación de nuevos esquemas de aprovechamiento, en dónde se unifiquen los esfuerzos entre todos los actores de la cadena.

    .row.mb-4
      .col-lg-6
        .tarjeta.color-verde3.p-2.mb-4 
          p.mb-0 <b>Código de colores propuesto por la GTC 24</b>

    p.mb-4 Para las entidades de salud si es obligatorio el código de colores que delegue el Manual para la Gestión Integral de Residuos Generados en la Atención en Salud y otras actividades, y se dictan otras disposiciones.

    .row.mb-0
      .col-lg-12
        .titulo-sexto.color-acento-contenido
          h5 Figura 7
          span Código de colores propuesto por la GTC 24
    .row.mb-0
      .col-lg-12
        .tarjeta.colorbasura.p-4
          .row.justify-content-center
            .col-lg-10
              .tarjeta--container.row
                .row
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo1.png', alt='Texto que describa la imagen')
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo2.png', alt='Texto que describa la imagen')
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo3.png', alt='Texto que describa la imagen')
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo4.png', alt='Texto que describa la imagen')
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo5.png', alt='Texto que describa la imagen')
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo6.png', alt='Texto que describa la imagen')
                  .col-md.mg
                    figure
                      img(src='@/assets/curso/tema7/residuo7.png', alt='Texto que describa la imagen')
    figcaption.mb-4 Nota. Manual para el manejo integral de residuos sólidos en el valle de aburra. Área metropolitana del valle de aburra (2016).  

    .row.mb-4
      .col-lg-4
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Características de los recipientes
    p.mb-4 Los tipos y capacidades de los recipientes, dependen de las características y tipos de residuos, el tipo y frecuencia del sistema de recolección y del espacio disponible para ellos.

    .tarteja.color-cuadroama.p-4.mb-4
      .row 
        .col-lg-6
          figure
            img(src='@/assets/curso/tema7/2.png', alt='Texto que describa la imagen')
        .col-lg-6
          p.mb-4 Frecuentemente se emplean bolsas, contenedores, canecas, cajas, entre otros. Sin embargo, según la norma GTC 24- Gestión Ambiental Residuos sólidos Guía para la separación en la fuente del 2009, se debe tener en cuenta lo siguiente, para su selección:
          ul.lista-ul--color
            li 
              i.fas.fa-check
              p.mb-2 A nivel doméstico se espera que los recipientes sean de material impermeable, liviano y resistente, de fácil cargue, de tal forma que facilite su transporte y se reduzca el impacto sobre el ambiente y la salud humana.
            li 
              i.fas.fa-check
              p.mb-2 Los recipientes de carácter retornable deberían permitir su fácil limpieza.
            li 
              i.fas.fa-check
              p.mb-2 Los recipientes que se empleen para presentar los residuos para recolección deberían evitar el contacto de los residuos con el entorno y con las personas encargadas de dicha recolección.
            li 
              i.fas.fa-check
              p.mb-2 Los recipientes tanto desechables como retornables deberían: proporcionar seguridad e higiene, permitir el aislamiento de los residuos con el entorno, tener una capacidad y volumen proporcional al peso, volumen y características de los residuos contenidos, ser de material resistente, preferiblemente reciclable, reutilizable o ambos y facilitar su cierre o amarre.
            li 
              i.fas.fa-check
              p.mb-2 En instalaciones multiusuario, comerciales e industriales pueden emplearse grandes contenedores de acopio.
    p.mb-4 Los recipientes para residuos infecciosos deben ser del tipo tapa y pedal y se identifican sus canecas con el logo de infeccioso, ver figura 8, si es químico algunas veces colocan el logo de una calavera y dicen el tipo de químico que se envasa. 
    .row.justify-content-center.mb-0
      .col-lg-8
        .titulo-sexto.color-acento-contenido.mb-0
          h5 Figura 8
          span Símbolo de Infecciosos
        figure
          img(src='@/assets/curso/tema7/3.png', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Plan de gestión Integral de Residuos. Universidad Industrial de Santander (2013).
    p.mb-0 Los recipientes para residuos peligrosos obligatoriamente deben tener tapa, con buen ajuste, bordes redondeados y boca ancha para facilitar su vaciado. Construidos en forma tal que, estando cerrados o tapados, no permitan la entrada de agua, insectos o roedores, ni el escape de líquidos por sus paredes o por el fondo. 
    p.mb-4 Los residuos reciclables usan el logo de reciclaje en los recipientes y para ordinarios usan algunas veces el logo circular, pero no es necesario el logo en ordinarios (Alcaldía Santiago de Cali,  2015).

    .row.mb-4
      .col-lg-2
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Bolsas
    .row.align-items-center.mb-4
      .col-lg-6
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-0
          p.mb-4 La resistencia de las bolsas debe soportar la tensión ejercida por los residuos contenidos y por su manipulación. El material plástico de las bolsas para residuos infecciosos, debe ser polietileno de alta densidad, o el material que se determine necesario para la desactivación o el tratamiento de estos residuos, la resistencia de cada una de las bolsas no debe ser inferior a 20 kg, ver figura 9.
          p.mb-0 Los colores de bolsas seguirán el código establecido por la organización y/o entidad territorial, serán de alta densidad y calibre mínimo de 1.4 para bolsas pequeñas y de 1.6 milésimas de pulgada para bolsas grandes, suficiente para evitar el derrame durante el almacenamiento en el lugar de generación, recolección, movimiento interno, almacenamiento central y disposición final de los residuos que contengan (Universidad Industrial de Santander, 2013).
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 9
          span Bolsas rojas
        figure.mb-0
          img(src='@/assets/curso/tema7/4.png', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Plan de gestión Integral de Residuos. Universidad Industrial de Santander (2013).
    
    .row.mb-4
      .col-lg-5
        .row
          .col-10
            .tarjeta.color-primario.p-3
              h4.mb-0 Recipientes para residuos Cortopunzantes

    .tarjeta.color-cuadroama.px-4.py-2.mb-4
      .row.align-items-center
        .col-lg-6
          p.mb-4 Los recipientes para residuos cortopunzantes son desechables y deben tener las siguientes características, ver figura 10:
          ul.lista-ul--color
            li 
              i.fas.fa-check
              p.mb-2 Rígidos, en polipropileno de alta densidad u otro polímero que no contenga P.V.C. 
            li 
              i.fas.fa-check
              p.mb-2 Resistentes a ruptura y perforación por elementos cortopunzantes.
            li 
              i.fas.fa-check
              p.mb-2 Con tapa ajustable o de rosca, de boca angosta, de tal forma que al cerrarse quede completamente hermético. Rotulados de acuerdo con la clase de residuo.
            li 
              i.fas.fa-check
              p.mb-2 Livianos y de capacidad no mayor a 2 litros.
            li 
              i.fas.fa-check
              p.mb-2 Ser resistentes, desechables y de paredes gruesa
        .col-lg-6
          .titulo-sexto.color-acento-contenido.mb-4
            h5 Figura 10
            span Recipiente rígido para corto punzantes
          figure.mb-0
            img(src='@/assets/curso/tema7/5.png', alt='Texto que describa la imagen')
          figcaption.mb-4 Nota. Plan de gestión Integral de Residuos. Universidad Industrial de Santander (2013).
    separador

    #t_7_4.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 7.4 Separación en la fuente

    .row.align-items-center.mb-4
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 11
          span Rotulación
        figure.mb-0
          img(src='@/assets/curso/tema7/6.png', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Material para la recogida selectiva bidones. Universidad de Cádiz (2016). 
      .col-lg-6
        p.mb-4 Los recipientes deben ir rotulados como se observa en la figura 11, con el nombre del generador, departamento, área o servicio al que pertenecen, el nombre del residuo que contienen, fecha de recolección y el símbolo de peligrosidad si es residuo peligroso.
        p.mb-4 Para la rotulación de los residuos peligrosos se realiza acorde a la normativa ICONTEC (2005) Norma técnica colombiana NTC1692 Transporte de mercancías peligrosas definiciones, clasificación, marcado, etiquetado y rotulado y el decreto 1609 de 2002 "Por el cual se reglamenta el manejo y transporte terrestre automotor de mercancías peligrosas por carretera".
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-0
          p.mb-0 El etiquetado tiene como objetivo principal identificar el residuo peligroso y reconocer la naturaleza del peligro que representa, alertando a las personas involucradas en el transporte o manejo sobre las medidas de precaución y prohibiciones. La etiqueta que se utilizara para la identificación de los residuos puede ser de diferentes estilos (Universidad de Cádiz, 2016).
    .row.mb-4
      .col-lg-5
        .row
          .col-12
            .tarjeta.color-primario.p-3
              h4.mb-0 Norma NFPA (National Fire Protection Association)
    p.mb-4 En residuos peligrosos pueden usarse diferentes tipos de pictogramas como el del rombo NFPA, ver figura 12.

    .row.justify-content-center.mb-4
      .col-lg-5
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 12
          span Rotulación
        figure.mb-0
          img(src='@/assets/curso/tema7/2.jpg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Rombo de riesgo NFPA. Gerry Mata (2012).

    .row.mb-4
      .col-lg-8
        .row
          .col-12
            .tarjeta.color-primario.p-3
              h4.mb-0 Sistema Globalmente Armonizado de clasificación y etiquetado de productos -SGA
    p.mb-2 Pictogramas como los del sistema globalmente armonizado, ver figuras 13 y 14.

    .row.align-items-center.mb-4
      .col-lg-6
        figure.mb-0
          img(src='@/assets/curso/tema7/7.png', alt='Texto que describa la imagen')
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-0
          h5 Figura 13
          span SGA
        figure.mb-0
          img(src='@/assets/curso/tema7/icon7.png', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Etiqueta SGA. MARBE Departamento químico (2016).
    .row.align-items-center.mb-4
      .col-lg-6
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').px-5.py-4.mb-0
          p.mb-2 Pictogramas
          ul.lista-ul--color
            li 
              i.fas.fa-check
              p.mb-0 <FONT COLOR="#D61B22"> Rojo: </FONT> representa los peligros físicos.
            li 
              i.fas.fa-check
              p.mb-0 <FONT COLOR="#05B770"> Verde: </FONT> representa los peligros para la salud.
            li 
              i.fas.fa-check
              p.mb-0 <FONT COLOR="#0540B7"> Rojo: </FONT> representa los peligros físicos.
        figure.mb-0
          img(src='@/assets/curso/tema7/icon8.png', alt='Texto que describa la imagen')
      .col-lg-6
        figure.mb-0
          img(src='@/assets/curso/tema7/8.png', alt='Texto que describa la imagen')
    
    .titulo-sexto.color-acento-contenido.mb-0
      h5 Figura 14
      span Pictogramas del SGA
    figure.mb-0
      img(src='@/assets/curso/tema7/icon9.png', alt='Texto que describa la imagen')
    figcaption.mb-4 Nota. Etiqueta SGA . MARBE Departamento químico (2016). 

    .row.mb-4
      .col-lg-4
        .row
          .col-12
            .tarjeta.color-primario.p-3
              h4.mb-0 Norma técnica NTC Colombiana 1692.
    p.mb-4 En la siguiente tabla encuentra los pictogramas más usados de acuerdo con la norma NTC1692, ver tabla 4.

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.color-azul.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/pdf.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h3.mb-1 Tabla 4 
                  p Pictogramas por medio de la NTC1692 la cual es la más usada en residuos.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
        p.mb-4 Los ejemplos más usuales se presentan en las siguientes figuras 15, 16 y 17:
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 15
          span Etiqueta de ejemplo para residuos peligrosos.
        figure.mb-0
          img(src='@/assets/curso/tema7/tabla2.svg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Plan de Gestión Integral de Residuos. IMPALA (2017).
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 16
          span Etiqueta de ejemplo para residuos peligrosos 2.
        figure.mb-0
          img(src='@/assets/curso/tema7/tabla3.svg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Procedimiento Manejo de residuos. Universidad Tecnológica de Pereira (2017).
    p.mb-4 Para los residuos no peligrosos su rotulación es colocar el nombre del residuo, quien lo genera , fecha de recolección y el logo de reciclaje si es para reciclar y si es ordinario o común no se requiere de logo solo de la identificación del residuo, algunas veces en los rótulos se coloca el peso o volumen del residuo si este no está en el rotulo debe estar en los registros de gestión de residuos sea en el registro de recolección o de almacenamiento de residuos o de entrega de residuos para así llevar los indicadores de gestión de generación de residuos.

    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 17
          span Rotulado de la universidad los andes ejemplo de residuos peligrosos
        figure.mb-0
          img(src='@/assets/curso/tema7/tabla4.svg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Procedimiento para la gestión y disposición de residuos sólidos y peligrosos. Universidad de los Andes (2012).
    separador

    #t_7_5.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 7.5 Separación en la fuente

    p.mb-4 Para identificar los residuos es importante recorrer la organización y detectar los puntos de generación de residuos, hacerse las preguntas que tipo de residuos se detecta en cada una de las etapas de producción y/o procesos en la organización, la mayoría de las veces se identifica por medio de la detección de los puntos ecológicos, pero también de las áreas en donde se generen residuos. Para esto es importante realizar una caracterización cualitativa por tanto se deberá definir por áreas el tipo de residuo que se genera. Para realizar esta identificación se puede facilitar por medio de un eco balance de proceso.
    p.mb-4 En la figura 18 se expone un ejemplo de eco balance de una organización litográfica.
    .titulo-sexto.color-acento-contenido.mb-2
      h5 Figura 18
      span Eco balance del proceso litográfico
    .row.mb-4
      .col-lg-11
        figure.mb-0
          img(src='@/assets/curso/tema7/fig1.svg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Diagnóstico ambiental en la industria litográfica. Adriana Guerrero (2013).
    .row.mb-4
      .col-lg-4
        .tarjeta.color-verde3.p-2
          p.mb-0 <b>ECOMAPA</b>
    p.mb-4 Por medio de un ECOMAPA, ver figuras 19 y 20, se realiza la Identificación de aspectos ambientales que se generan en la organización entre estos se puede identificar la generación de los residuos por medio de pictogramas en el plano, mediante el empleo de un ecomapa como herramienta de diagnóstico.

    .row.justify-content-center.mb-2
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 19
          span Ecomapa empresa litográfica ejemplo
        figure.mb-0
          img(src='@/assets/curso/tema7/fig2.svg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Diagnóstico ambiental en la industria litográfica. Adriana Guerrero (2013). 
    .row.justify-content-center.mb-2
      .col-lg-6
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 20
          span Ecomapa laboratorio ejemplo
        figure.mb-0
          img(src='@/assets/curso/tema7/fig3.svg', alt='Texto que describa la imagen')
        figcaption.mb-4 Nota. Plan de manejo integral de residuos sólidos y líquidos. Empresa de acueducto y alcantarillado y aseo de Madrid (2018).
    p.mb-4 Posteriormente se realizará una caracterización cuantitativa que se explica en el posterior tema para realizar metodología de cuantificación de estos, como se muestra en la siguiente tabla 5.
    .titulo-sexto.color-acento-contenido.mb-2
      h5 Tabla 5
      span Caracterización cuantitativa
    .tabla-a.color-acento-botones 
      table(style='background-color: #E2EACB')
        caption Nota. Guía para elaboración y presentación del plan de gestión integral de residuos hospitalarios y similares-pgirhs aplicado a microgeneradores. Área Metropolitana de Bucaramanga (2002). 
        thead
          tr
            th
            <th colspan="4">CARACTERIZACIÓN CUANTITATIVA</th>
            <th colspan="4"> </th>
        tbody
          tr
            td <b>DÍA</b>
            <td colspan="4"> <b>Residuos no Peligrosos</b> </td>
            <td colspan="4"> <b>Residuos Peligrosos</b> </td>
          tr
            <td rowspan="2"> </td>
            <td rowspan="2"> <b>Biodegradables (Kg)</b> </td>
            <td rowspan="2"> <b>Reciclables (Kg)</b> </td> 
            <td rowspan="2"> <b>Inertes (Kg)</b> </td>
            <td rowspan="2"> <b>Ordinarios(Kg)</b> </td>
            <td colspan="2"> <b>INFECCIOSOS O DE RIESGO BIOLOGICO</b> </td>
            <td colspan="2"> <b>QUIMICO</b> </td>
          tr
            td <b>Biosanitarios (kg)</b>
            td <b>Cortopunzantes (kg)</b>
            td <b>Fármacos (kg)</b>
            td <b>Reactivos (kg)</b>
          tr
            td <b>1</b>
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            td <b>2</b>
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            td <b>3</b>
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            td <b>4</b>
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            td <b>5</b>
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            td <b>6</b>
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            td <b>7</b>
            td
            td
            td
            td
            td
            td
            td
            td



</template>

<script>
export default {
  name: 'Tema7',
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
