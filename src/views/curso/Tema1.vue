<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. ¿Qué es la Inteligencia Artificial?'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-8
        p(data-aos="fade-left").mb-4 La Inteligencia Artificial es una rama de la informática que estudia los diferentes mecanismos que permiten a las computadoras realizar las mismas operaciones que el ser humano. Desde tiempos remotos, los científicos y los filósofos naturalistas, se interesaron en el estudio de la inteligencia humana. La idea de intentar comprender el comportamiento de nuestro intelecto y de nuestros sentimientos al punto de poder reproducirlos en una máquina, fue una de las ideas más ambiciosas en la historia de la humanidad.
    
        .bg-color-2.p-4(data-aos="fade-left").mb-4
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Lo importante es determinar la conducta resultante y tener en cuenta el mecanismo desde el cual se produce el comportamiento. Así, si se pudiera implementar un software que desempeñara una función tan bien como la desempeña un ser humano, entonces la Inteligencia Artificial sería una realidad.
    
        p(data-aos="fade-left").mb-4 En la actualidad la Inteligencia Artificial se puede clasificar de diferentes formas y, la primera es, de acuerdo a cómo se relacionan con la inteligencia humana; a continuación, se muestran  los diferentes tipos de esta categoría y su principal característica.
    
      .col-lg-4
        figure
          img(src="@/assets/curso/tema1/2.png", data-aos="zoom-in")

    .bg-full-width-2.bg-fondo-2
      .px-4.px-md-5.pb-md-3
        .row.align-items-start.mb-5
          .col-lg-4
            figure
              img(src="@/assets/curso/tema1/3.png", alt="").mb-4.mb-lg-0
          .col-lg-8

            AcordionA(tipo="b")
              .div(titulo="Sistemas que actúan como humanos")
                p Estudio de como hacer computadoras que realicen las cosas que la gente hace mejor.
        
              .div(titulo="Sistemas que piensan como humanos")
                p Hacer a las computadoras pensar.
                p Máquinas con mente.

        
              .div(titulo="Sistemas que actúan racionalmente")
                p Buscan imitar la lógica humana.
        
              .div(titulo="Sistemas que piensan racionalmente")
                p No solo piensan de manera racional, sino que además toman acciones óptimas para alcanzar un objetivo.


        p.mb-5 De acuerdo con la capacidad de los sistemas, se plantean #[strong 3 tipos de IA; IA débil, IA general y la IA superinteligente], donde el nivel de comprensión y capacidad, va aumentando desde tareas puntuales hasta llegar a niveles de inteligencia que superarían la de un ser humano; estudiemos algunas características de esta clasificación.

        //- div.row.justify-content-center.align-items-stretch.mb-5
        //-   div.col-lg-4.mb-4(data-aos="zoom-in-up")
        //-     div.bg-color-white.box-shadow.px-4.py-5.h-100
        //-       img.mx-auto.d-block.mb-4(
        //-         src="@/assets/curso/tema1/4.svg"
        //-         alt=""
        //-         style="width: 90px"
        //-       )
        //-       h5.text-center IA Débil o Estrecha (Narrow AI)
        //-       p.text-center Diseñada para realizar tareas específicas (reconocimiento facial, asistentes virtuales como Siri o Alexa).  
        //-       p.text-center No tiene conciencia ni comprensión general del mundo.
        
        //-   div.col-lg-4.mb-4(data-aos="zoom-in-up")
        //-     div.bg-color-white.box-shadow.px-4.py-5.h-100
        //-       img.mx-auto.d-block.mb-4(
        //-         src="@/assets/curso/tema1/5.svg"
        //-         alt=""
        //-         style="width: 90px"
        //-       )
        //-       h5.text-center IA General (General AI o AGI - Artificial General Intelligence)
        //-       p.text-center Es capaz de aprender y realizar cualquier tarea cognitiva a nivel humano. 
        //-       p.text-center No existe aún, pero es un objetivo en el desarrollo de la IA.
        
        //-   div.col-lg-4.mb-4(data-aos="zoom-in-up")
        //-     div.bg-color-white.box-shadow.px-4.py-5.h-100
        //-       img.mx-auto.d-block.mb-4(
        //-         src="@/assets/curso/tema1/6.svg"
        //-         alt=""
        //-         style="width: 90px"
        //-       )
        //-       h5.text-center IA Superinteligente (Super AI)
        //-       p.text-center Superaría la inteligencia humana en todos los aspectos.
        //-       p.text-center Es teórica por ahora y plantea dilemas éticos y de control.
    

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slide-1.png")
            .col-lg-7
              h5 IA Débil o Estrecha (Narrow AI)
              p Diseñada para realizar tareas específicas (reconocimiento facial, asistentes virtuales como Siri o Alexa).
              p No tiene conciencia ni comprensión general del mundo.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slide-2.png")
            .col-lg-7
              h5 IA General (General AI o AGI - Artificial General Intelligence)
              p Es capaz de aprender y realizar cualquier tarea cognitiva a nivel humano. 
              p No existe aún, pero es un objetivo en el desarrollo de la IA.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slide-3.png")
            .col-lg-7
              h5 IA Superinteligente (Super AI)
              p Superaría la inteligencia humana en todos los aspectos.
              p Es teórica por ahora y plantea dilemas éticos y de control.
    
    .bg-full-width-2.bg-fondo-3
      .px-4.px-md-5.pb-md-3
    
        p.mb-5 Ahora, según su funcionalidad, los sistemas de IA se pueden clasificar en: IA Reactiva, IA con Memoria Limitada, Teoría de la Mente y la IA Autoconsciente, donde se mide su capacidad de responder e integrarse en procesos humanos . Sus principales características se muestran a continuación.


        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/7.svg"
                alt=""
                style="width: 90px"
              )
              h5.mb-0.text-center IA Reactiva
              p.mb-0.text-center Solo responde a estímulos sin memoria, ni aprendizaje.
              p.mb-0.text-center No puede adaptarse a situaciones nuevas.

        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/8.svg"
                alt=""
                style="width: 90px"
              )
              h5.mb-0.text-center IA con Memoria Limitada
              p.mb-0.text-center Puede usar datos pasados, por un tiempo corto, para tomar decisiones..
              p.mb-0.text-center Es la IA usada en autos autónomos y reconocimiento facial.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/9.svg"
                alt=""
                style="width: 90px"
              )
              h5.mb-0.text-center Teoría de la Mente
              p.mb-0.text-center Aún en desarrollo.
              p.mb-0.text-center Buscan que la IA entienda las emociones y las intenciones humanas.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/10.svg"
                alt=""
                style="width: 90px"
              )
              h5.mb-0.text-center IA Autoconsciente
              p.mb-0.text-center Es completamente teórica. 
              p.mb-0.text-center Tendría conciencia propia y emociones.


    p.mb-5 Desde sus inicios a mediados del siglo pasado, la Inteligencia Artificial ha proporcionado la base para una gran variedad de aplicaciones relacionadas con el manejo de datos y el procesamiento de la información; por ello, se ha considerado que la IA abarca cuatro campos de gran importancia, los cuales son: 


    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-10
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema1/info1.png', alt='', style="max-width: 610px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="50%" y="5%" numero="+")
                h5 Robótica y visión artificial
                p Se centra en la creación de máquinas capaces de interactuar con el mundo físico.
    
              .bg-color-white.box-shadow.p-3(x="30.5%" y="34%" numero="+")
                h5 Énfasis en la toma de dec
                p Se busca optimizar los procesos mediante análisis algorítmicos.Contenido punto 2
    
              .bg-color-white.box-shadow.p-3(x="70%" y="34%" numero="+")
                h5 Procesamiento de lenguaje natural
                p Es fundamental para la comunicación entre usuarios y sistemas tecnológicos.
    
              .bg-color-white.box-shadow.p-3(x="50%" y="70%" numero="+")
                h5 Aprendizaje automático
                p Está íntimamente relacionado con todas las aplicaciones de IA y aborda la capacidad de las máquinas para aprender de los datos.

    

    p A continuación, se muestra una tabla de resumen de las clasificaciones y ejemplos de posibles implementaciones de los diferentes tipos de IA.

    .titulo-figura.mb-2
      h5 Tabla 1. 
      span Resumen de clasificaciones de Inteligencia Artificial
    

    .tabla-a.color-acento-contenido.mb-5
      table#Tabla1.bordes
        thead
          tr
            th.bg-color-tabla.text-white Clasificación
            th.bg-color-tabla.text-white Categoría
            th.bg-color-tabla.text-white Descripción
            th.bg-color-tabla.text-white Ejemplo
        tbody.bg-color-4
          // Por comparación con la inteligencia humana
          tr.bordes
            td(rowspan="4") #[strong Por comparación con la inteligencia humana]
            td Sistemas que actúan como humanos
            td Imita el comportamiento humano, en tareas específicas.
            td Chatbots, robots humanoides, reconocimiento de voz.
          tr.bordes
            td Sistemas que piensan como humanos
            td Modela el pensamiento humano en la toma de decisiones y el aprendizaje.
            td Redes neuronales, sistemas expertos, IA en juegos estratégicos.
          tr.bordes
            td Sistemas que piensan racionalmente
            td Aplican lógica y razonamiento matemático, sin imitar el pensamiento humano.
            td Inferencia lógica, motores de reglas en sistemas expertos, optimización de rutas.
          tr.bordes
            td Sistemas que actúan racionalmente
            td Toman decisiones óptimas sin necesidad de imitar la inteligencia humana.
            td Autos autónomos, trading algorítmico, sistemas de recomendación.

          // Por técnicas utilizadas
          tr.bordes
            td(rowspan="4") #[strong Por técnicas utilizadas]
            td Aprendizaje Automático (Machine Learning)
            td Algoritmos que aprenden patrones a partir de datos, sin reglas fijas.
            td Detección de fraudes, predicción de tendencias.
          tr.bordes
            td Aprendizaje Profundo (Deep Learning)
            td Redes neuronales profundas para reconocimiento de patrones complejos.
            td Diagnóstico de cáncer en imágenes médicas, IA en arte.
          tr.bordes
            td Procesamiento de Lenguaje Natural (NLP)
            td Permite que la IA entienda y genere lenguaje humano.
            td ChatGPT, traducción automática, análisis de sentimientos.
          tr.bordes
            td Visión por Computadora
            td Análisis e interpretación de imágenes y videos.
            td Seguridad en aeropuertos, vehículos autónomos, detección de enfermedades en imágenes médicas.

          // Por capacidad
          tr.bordes
            td(rowspan="3") #[strong Por capacidad]
            td IA Débil (Narrow AI)
            td Realiza tareas específicas sin conciencia ni razonamiento general.
            td Chatbots, asistentes virtuales (Siri, Alexa), algoritmos de recomendación (Netflix, YouTube).
          tr.bordes
            td IA General (AGI)
            td Aprende y razona como un humano, en cualquier tarea cognitiva.
            td IA hipotética en robots que pueden realizar múltiples tareas sin entrenamiento específico.
          tr.bordes
            td IA Superinteligente (Super AI)
            td Supera a los humanos en todas las capacidades cognitivas.
            td IA teórica capaz de resolver problemas científicos mejor que cualquier humano.

          // Por funcionalidad
          tr.bordes
            td(rowspan="4") #[strong Por funcionalidad]
            td IA Reactiva
            td No tiene memoria ni aprendizaje; solo responde a estímulos.
            td Deep Blue (ajedrez), IA en videojuegos básicos.
          tr.bordes
            td IA con Memoria Limitada
            td Usa datos pasados para mejorar decisiones, pero no aprende a largo plazo.
            td Autos autónomos, reconocimiento facial.
          tr.bordes
            td Teoría de la Mente
            td Busca comprender emociones e intenciones humanas (en desarrollo).
            td Asistentes virtuales con inteligencia emocional (futuro).
          tr.bordes
            td IA Autoconsciente
            td Tiene conciencia propia y emociones (hipotética).
            td Robots con autoconciencia, inteligencia similar a la humana.


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/42319" target="_blank" rel="noopener noreferrer") Meseguer González, P. & López de Mántaras Badia, R. (2017). Inteligencia Artificial: ( ed.). Editorial CSIC Consejo Superior de Investigaciones Científicas. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=Y8PUJeGQVZo" target="_blank" rel="noopener noreferrer") ParqueSoft Pasto. (2024, 28 de octubre). Herramientas de Inteligencia Artificial para la Productividad.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
