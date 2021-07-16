<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Desarrollo de habilidades digitales para la construcción de contenido digital
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Desarrollo de habilidades digitales para la construcción de contenido digital
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 2810017
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/nIoyamplJoE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

 
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p ¡Hola! La producción de contenidos digitales, hace un tiempo, sólo estaba disponible para profesionales y empresas con los recursos suficientes para producirlos.

    p Hoy en día, los avances en temas tecnológicos nos permiten tener a la mano herramientas y plataformas con las que cualquier persona, con disposición de aprendizaje y un objetivo claro de comunicación y conexión a internet, tendrá todo lo necesario para la producción y distribución de contenidos.

    p Soy Jesualdo Morantes, quien los acompañará en el curso de desarrollo de habilidades para la producción de contenidos digitales, donde identificaremos algunos conceptos básicos, y de manera práctica, aprenderemos el flujo de trabajo que nos permitirá construir piezas digitales, desde la planeación, el uso de herramientas, producción y publicación de contenidos.
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p El Servicio Nacional de Aprendizaje SENA dentro de sus funciones principales tiene organizar, desarrollar, administrar y ejecutar programas de formación profesional integral, en coordinación y en función de las necesidades sociales y del sector productivo (Servicio Nacional de Aprendizaje - SENA, 1994) En su Plan Estratégico Institucional 2019 2022, uno de sus objetivos es formar el talento humano pertinente que demanda el sector empresarial del país (SENA, Servicio Nacional de Aprendizaje, 2018) el cual se encuentra alineado con una de las estrategias del Plan Nacional de Desarrollo 2018 2022 de promocionar una política de Estado para la transformación digital y el aprovechamiento de la cuarta revolución industrial, a través de la interoperabilidad de plataformas, contacto a través del Portal Único del Estado, uso de tecnologías emergentes, seguridad digital, formación en talento digital, y fomento del ecosistema de emprendimiento (Departamento Nacional de Planeación, 2018) y los objetivos de desarrollo sostenibles de la ONU en referencia a la reducción de las desigualdades (impact-digital-technologies, 2019).
    p En tal sentido, el Sena diseñó la ruta 
      strong FORTALECIMIENTO DE LAS HABILIDADES DIGITALES PARA LA VIDA Y LA PRODUCTIVIDAD 
      | que consta de 4 programas, el segundo programa de esta ruta DESARROLLO DE HABILIDADES DIGITALES PARA LA CONSTRUCCIÓN DE CONTENIDO DIGITAL, el cual brinda elementos conceptuales y herramientas que permitan desarrollar y fortalecer habilidades en la era digital para que los ciudadanos puedan adaptarse a las necesidades de las empresas y la sociedad, que son parte de las competencias propuestas por la industria 4.0, además de ser un aporte que propicien el desarrollo y fortalecimiento de posibles emprendimientos sostenibles.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    p Operar herramientas informáticas y digitales de acuerdo con protocolos y manuales técnicos.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    p Para la realización de este programa, es necesario que el aprendiz tenga un adecuado manejo de las siguientes herramientas informáticas y de comunicación:
    p Correo electrónico, Chats, Messenger, procesadores de texto, software de presentación, internet, navegadores, otros sistemas y herramientas tecnológicas para la formación virtual.
      
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso

    p N/A
     

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica

    p Basada en el aprendizaje autogestionado, donde el aprendiz es el encargado y responsable de su propia gestión académica, mediante un papel activo en el estudio de los temas y el desarrollo de actividades encaminadas a promover las competencias propuestas en el programa.  Para ello, el curso le orienta de manera práctica y puntual, a través de una serie de módulos con recursos formativos apoyados en TIC, y le estimula de manera permanente al alcance de los resultados de aprendizaje y el pensamiento crítico.
     


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
