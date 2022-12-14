<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Como empezar un diagnóstico de residuos
    
    .row.align-items-center.mb-4
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema5/1.png', alt='Texto que describa la imagen')   
      .col-lg-6
        p.mb-4 Para diseñar y poner en funcionamiento el Manejo Integral de Residuos, deben tenerse en cuenta las actividades que se desarrollan en el sitio de trabajo, de forma real y clara, con propuestas de mejoramiento continuo de los procesos y orientado a la prevención y a la minimización de riesgos para la salud y el ambiente. El compromiso debe responder claramente a las preguntas qué, cómo, cuándo, dónde, por qué, para qué y con quién.
        p.mb-4 Como se ve, la estructura que se plantea es la de minimizar la generación y maximizar los aprovechamientos, de tal manera que siempre se disponga de la menor cantidad de residuos en los rellenos sanitarios, como primer paso del manejo integral de residuos se requiere realizar un diagnóstico del estado actual de la gestión de residuos en la organización, para ello se plantea los siguientes pasos:

    .row.align-items-center.mb-4
      .col-lg-6
        .tarjeta.color-verde3.p-2.mb-4 
          p.mb-0 <b>Creación del grupo Administrativo de Gestión Ambiental y Sanitaria (GAGAS).</b>
        p.mb-4 El grupo GAGAS es obligatorio para entidades de salud, pero se propone crearlo para las organizaciones para un mejor manejo de la gestión ambiental, crear un Grupo Administrativo de Gestión Ambiental y Sanitaria (GAGAS) que garantice la correcta formulación e implementación del Plan de Gestión Integral de Residuos (PGIRS).  Por tanto, las personas que integran el grupo serán el representante legal o su similar y demás personas, conforme a las condiciones específicas del establecimiento entre los cuales puede ser auxiliares, operarios, entre otros; que laboran y son los encargados de dar cumplimiento al Compromiso Institucional, y los responsables del plan en todos sus componentes. Para la estructura funcional se tendrá en cuenta la respectiva jerarquía que exista en el establecimiento.
      .col-lg-6
        figure.mb-2
          img(src='@/assets/curso/tema5/2.png', alt='Texto que describa la imagen')  

    figure.mb-4
      img(src='@/assets/curso/tema5/3.png', alt='Texto que describa la imagen')  

    p.mb-4 Dentro de las funciones del GAGAS son:

    .row.mb-4
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>a.</b>Realizar el diagnóstico ambiental y sanitario.
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>b.</b>Formular el Compromiso Institucional.
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>c.</b>Diseñar el Plan De Gestión Integral De Residuos.
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>d.</b>Diseñar la estructura funcional y asignar responsabilidades. 

    .row.mb-4
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>e.</b>Definir y establecer mecanismos de coordinación. 
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>f.</b>Gestionar el presupuesto del plan.
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>g.</b>Velar por la ejecución del plan.
      .col-lg-3
        .tarjeta.color-verde4.p-3
          p.mb-0 <b>h.</b>Elaborar informes y reportes a las autoridades de vigilancia y control.

</template>

<script>
export default {
  name: 'Tema5',
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
