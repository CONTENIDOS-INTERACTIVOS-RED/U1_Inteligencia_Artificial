<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'3. Aplicaciones de la IA'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
  
      .bg-color-3.mb-5(data-aos="fade-up")
        .row.justify-content-center.align-items-center
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema3/1.png', alt='')
          .col-lg
            .p-4
              p.mb-0(data-aos="fade-up") Es importante en cuenta que la Inteligencia Artificial, desde su concepto, parte de la idea de que al usar herramientas computacionales, se realizan actividades, que asemejan al comportamiento humano, lo que tiene una gran variedad de aplicaciones y de campos de acciones; a continuación, se relacionan los más relevantes y de interés, en la actualidad.


      .titulo-segundo.mb-5(data-aos="fade-up")
        h2 #[span 3.1] Sector de la salud
      

      .row.mb-5
        .col-lg-8
          p La Inteligencia Artificial ha demostrado su potencial en el campo de la salud, con aplicaciones que van desde el diagnóstico médico asistido por computadora, hasta el desarrollo de fármacos y la optimización de los procesos de gestión hospitalaria.
          p A continuación, se relacionan los principales entornos de aplicación de la IA en el sector:

        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/2.svg", alt="")


      .row.align-items-start.mb-5
        .col-lg-8
          AcordionA(tipo="b")
            .div(titulo="Diagnóstico médico")
              p Algoritmos de #[em Deep Learning] analizan imágenes médicas (radiografías, tomografías, resonancias), para detectar enfermedades como el cáncer de piel y enfermedades pulmonares, entre otras.
      
            .div(titulo="Medicina personalizada")
              p La IA analiza datos genéticos y clínicos, para recomendar tratamientos adaptados a cada paciente.
      
            .div(titulo="Asistentes virtuales médicos")
              p Chatbots y asistentes de voz, ayudan a responder preguntas sobre síntomas y medicamentos.
      
            .div(titulo="Descubrimiento de fármacos")
              p La IA acelera la identificación de nuevos medicamentos, reduciendo costos y tiempos de desarrollo.
      
        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/3.png", alt="").mb-4.mb-lg-0


      .titulo-figura.mb-2
        h5 Tabla 2. 
        span Aplicaciones de la IA en el sector de la salud

      .tabla-a.color-acento-contenido.mb-5
        table#Tabla2.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td Diagnóstico y detección de enfermedades
              td Análisis de imágenes médicas, detección temprana, interpretación de pruebas.
              td #[em DeepMind] detecta enfermedades oculares con IA.
            tr.bordes
              td Desarrollo de medicamentos y terapias
              td Descubrimiento de fármacos, simulación química, medicina personalizada.
              td #[em AlphaFold] predice estructuras de proteínas para biomedicina.
            tr.bordes
              td Asistentes virtuales y telemedicina
              td #[em Chatbots] médicos, evaluación de síntomas, monitoreo remoto.
              td #[em Babylon Health] analiza síntomas y sugiere consultas.
            tr.bordes
              td Gestión hospitalaria
              td Optimización de recursos, predicción de demanda, manejo de historiales.
              td #[em Mount Sinai Hospital] usa IA para predecir ocupación hospitalaria.
            tr.bordes
              td Genómica y medicina de precisión
              td Análisis de ADN, predicción de riesgos genéticos, terapias personalizadas.
              td #[em IBM Watson] recomienda tratamientos oncológicos.
            tr.bordes
              td Robótica en salud
              td Cirugía asistida, rehabilitación, asistencia en cuidados de ancianos.
              td #[em Robot Da Vinci] realiza cirugías de precisión.


      .titulo-segundo.mb-5(data-aos="fade-up")
        h2 #[span 3.2] Sector financiero

      .bg-full-width-2.bg-fondo-4
        .px-4.px-md-5.pb-md-3
          p La Inteligencia Artificial en el sector financiero ha logrado optimizar procesos, mejorar la seguridad y ofrecer servicios más personalizados; algunas de sus principales aplicaciones en los siguientes ámbitos:


          div.row.justify-content-center.align-items-stretch.mb-5
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/4.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Detección de fraudes]
                p.text-center Algoritmos de Machine Learning identifican patrones sospechosos en transacciones y prevenir fraudes financieros.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/5.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Análisis de riesgo crediticio]
                p.text-center La IA evalúa historial de crédito para otorgar préstamos de manera más eficiente.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/6.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Trading algorítmico]
                p.text-center Los sistemas de IA analizan datos en tiempo real y ejecutan operaciones bursátiles con mayor precisión.

            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/7.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Atención al cliente]
                p.text-center Chatbots en bancos brindan asistencia automatizada 24/7.

          p En la siguiente tabla se muestran ejemplos en la realidad de aplicaciones, en el sector financiero.

      .titulo-figura.mb-2
        h5 Tabla 3. 
        span Aplicaciones de la IA en el sector financiero

      .tabla-a.color-acento-contenido.mb-5
        table#Tabla3.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Automatización y eficiencia]
              td Procesamiento de transacciones, asesoramiento financiero, optimización de procesos.
              td Citibank utiliza IA para mejorar la gestión de cuentas.
            tr.bordes
              td #[strong Detección de fraudes y seguridad]
              td Análisis de patrones sospechosos, autenticación biométrica, ciberseguridad.
              td Mastercard y Visa utilizan IA para prevenir fraudes.
            tr.bordes
              td #[strong Análisis de riesgo y crédito]
              td Modelos de #[em scoring] crediticio, evaluación de préstamos, predicción de impagos.
              td #[em ZestFinance] analiza clientes sin historial crediticio.
            tr.bordes
              td #[strong #[em Trading] algorítmico]
              td #[em Trading] de alta frecuencia, predicción de mercados, gestión de portafolios.
              td BlackRock utiliza IA en Aladdin, para inversiones.
            tr.bordes
              td #[strong Atención al cliente y banca digital]
              td #[em Chatbots], reconocimiento de voz, análisis de sentimiento.
              td Bank of America utiliza a Erica como asistente virtual.
            tr.bordes
              td #[strong Cumplimiento regulatorio]
              td Monitoreo de transacciones, auditorías automatizadas, análisis de documentos.
              td HSBC utiliza IA para detectar lavado de dinero.
            tr.bordes
              td #[strong #[em Fintech] y la innovación en pagos]
              td Pagos digitales, créditos instantáneos, gestión financiera personal.
              td PayPal utiliza IA para detectar fraudes en pagos.



      .titulo-segundo.mb-5(data-aos="fade-up")
        h2 #[span 3.3] Industria y manufactura


      .bg-full-width-2.bg-fondo-4
        .px-4.px-md-5.pb-md-3
          p La IA, ha optimizado la producción y mejorado la seguridad en fábricas, desde procesos de mantenimiento hasta la optimización de la cadena de suministro; sus principales aportaciones se encuentran en los campos:


          div.row.justify-content-center.align-items-stretch.mb-5
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/8.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Mantenimiento predictivo]
                p.text-center Sensores y la IA, detectan fallos en máquinas antes de que ocurran, reduciendo tiempos de inactividad.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/9.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Robots industriales]
                p.text-center Brazos robóticos con IA, automatizan tareas repetitivas en fábricas.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/10.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Control de calidad]
                p.text-center Sistemas de visión artificial detectan defectos en productos, durante la fabricación.

            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/11.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Optimización de cadenas de suministro]
                p.text-center La IA predice la demanda de productos y gestiona el inventario, de manera eficiente.

          p En la siguiente tabla se muestran ejemplos en la realidad de aplicaciones, en el sector financiero.

      .titulo-figura.mb-2
        h5 Tabla 4. 
        span Aplicaciones de la IA en los sectores de industria y manufactura


      .tabla-a.color-acento-contenido.mb-5
        table#Tabla4.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Automatización y robótica industrial]
              td Robots autónomos, #[em cobots], optimización de ensamblaje.
              td Tesla utiliza robots inteligentes en su producción.
            tr.bordes
              td #[strong Mantenimiento predictivo]
              td Análisis de sensores, detección temprana de fallos, reducción de costos.
              td General Electric monitorea turbinas con IA.
            tr.bordes
              td #[strong Control de calidad]
              td Visión artificial, inspección automatizada, reducción de desperdicios.
              td BMW utiliza IA para la inspección de pintura en autos.
            tr.bordes
              td #[strong Logística y cadena de suministro]
              td Optimización de rutas, gestión de inventarios, almacenes automatizados.
              td Amazon utiliza IA y robots, en sus centros logísticos.
            tr.bordes
              td #[strong Optimización de energía y sostenibilidad]
              td Reducción de consumo, reciclaje automatizado, minimización de residuos.
              td Siemens optimiza el consumo energético en fábricas.
            tr.bordes
              td #[strong Diseño y prototipado]
              td Generación de diseños, simulaciones, fabricación aditiva.
              td Autodesk optimiza el diseño en la industria aeroespacial.


      .titulo-segundo.mb-5(data-aos="fade-up")
        h2 #[span 3.4] Transporte y movilidad
      

      .row.mb-5
        .col-lg-8
          p La Inteligencia Artificial ha revolucionado el sector del transporte y la movilidad, mejorando la eficiencia, seguridad y sostenibilidad y sus aplicaciones van desde vehículos autónomos hasta optimización del tráfico, con la IA redefiniendo la manera en que nos movemos; a continuación, se describen las principales áreas y aplicaciones de la IA en el transporte.


        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/12.svg", alt="")

      .titulo-figura.mb-2
        h5 Tabla 5. 
        span Aplicaciones de la IA en el sector transporte


      .tabla-a.color-acento-contenido.mb-5
        table#Tabla5.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Vehículos autónomos y asistencia de conducción]
              td Conducción autónoma, asistentes de conducción, gestión de flotas.
              td Tesla y Waymo desarrollan autos autónomos.
            tr.bordes
              td #[strong Optimización del tráfico y movilidad urbana]
              td Semáforos inteligentes, predicción de congestión, gestión de estacionamientos.
              td Singapur utiliza IA para controlar el tráfico.
            tr.bordes
              td #[strong IA en la industria aeroespacial y marítima]
              td Rutas optimizadas, mantenimiento predictivo, aviones y barcos autónomos.
              td Rolls-Royce desarrolla barcos autónomos.
            tr.bordes
              td #[strong Logística y transporte de carga]
              td Optimización de rutas, gestión de almacenes, mantenimiento predictivo.
              td UPS utiliza IA para optimizar rutas de entrega.
            tr.bordes
              td #[strong Micromovilidad y transporte sostenible]
              td Bicicletas y #[em scooters] eléctricos inteligentes, monitoreo ambiental.
              td Lime utiliza IA en su flota de #[em scooters] eléctricos.


      .titulo-segundo.mb-5(data-aos="fade-up")#Seccion35
        h2 #[span 3.5] Comercio y #[em marketing]



      .row.mb-5
        .col-lg-8
          p La Inteligencia Artificial ha permitido a las empresas ofrecer experiencias personalizadas, mejorar la eficiencia y optimizar estrategias de venta; sus aplicaciones van desde la recomendación de productos, hasta la automatización de campañas publicitarias; la IA está transformando la forma en que las marcas interactúan con los consumidores. A continuación, se relacionan las principales aplicaciones en este campo.

        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/13.svg", alt="")




      .titulo-figura.mb-2
        h5 Tabla 6. 
        span Aplicaciones de la IA en comercio y marketing

      .tabla-a.color-acento-contenido.mb-5
        table#Tabla6.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Personalización de la experiencia del cliente]
              td Recomendaciones, #[em chatbots], análisis de sentimientos.
              td Amazon y Netflix utilizan IA para personalizar contenido.
            tr.bordes
              td #[strong Publicidad digital y automatización de #[em marketing]]
              td Segmentación de audiencias, generación de contenido, análisis de tendencias.
              td Google Ads optimiza anuncios con IA.
            tr.bordes
              td #[strong Optimización del comercio electrónico]
              td Precios dinámicos, gestión de inventarios, prevención de fraudes.
              td Alibaba utiliza IA para ajustar precios, en tiempo real.
            tr.bordes
              td #[strong Logística y cadena de suministro inteligente]
              td Optimización de rutas, automatización de almacenes, monitoreo de envíos.
              td Amazon gestiona almacenes con IA y robots.
            tr.bordes
              td #[strong Análisis predictivo y comportamiento del consumidor]
              td Predicción de demanda, ajuste de surtido, fidelización de clientes.
              td Walmart utiliza IA para prever la demanda de productos.



      .titulo-segundo.mb-5(data-aos="fade-up")#Seccion36
        h2 #[span 3.6] Educación


      .bg-full-width-2.bg-fondo-4
        .px-4.px-md-5.pb-md-3
          p La Inteligencia Artificial (IA), está revolucionando la educación al personalizar el aprendizaje, mejorar la enseñanza y optimizar la gestión administrativa; sus aplicaciones permiten una educación más accesible, eficiente e inclusiva. A continuación, se presentan las principales aplicaciones de la IA en este sector:


          div.row.justify-content-center.align-items-stretch.mb-5
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/14.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Plataformas de aprendizaje adaptativo]
                p.text-center Los sistemas ajustan el contenido, según el progreso del estudiante.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/15.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Asistentes de tutoría virtual]
                p.text-center La IA responde dudas y ayuda a los alumnos en tiempo real.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/16.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Automatización de tareas administrativas]
                p.text-center Reduce la carga de los docentes en tareas repetitivas.

            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/17.svg"
                  alt=""
                  style="width: 90px"
                )
                p.mb-0.text-center #[strong Análisis del desempeño estudiantil]
                p.text-center Identifica estudiantes en riesgo y sugiere estrategias de mejora.

      .titulo-figura.mb-2
        h5 Tabla 7. 
        span Aplicaciones de la IA en sector educativo


      .tabla-a.color-acento-contenido.mb-5
        table#Tabla7.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Personalización del aprendizaje]
              td Plataformas adaptativas, recomendación de contenido, tutoría con IA.
              td Duolingo ajusta lecciones, según el nivel del usuario.
            tr.bordes
              td #[strong Asistencia a los docentes]
              td Corrección automática, generación de planes de estudio, detección de plagio.
              td Turnitin utiliza IA, para identificar contenido copiado.
            tr.bordes
              td #[strong #[em Chatbots] y asistentes virtuales]
              td Respuestas automáticas, tutorías 24/7, interacción con lenguaje natural.
              td Socratic de Google responde preguntas con IA.
            tr.bordes
              td #[strong Gestión y administración educativa]
              td Inscripciones automáticas, análisis de rendimiento, optimización de horarios.
              td Arizona State University utiliza IA para mejorar la retención estudiantil.
            tr.bordes
              td #[strong Educación inclusiva y accesible]
              td Traducción en tiempo real, reconocimiento de voz, lectura de textos en voz alta.
              td Microsoft Immersive Reader ayuda a los estudiantes con dislexia.
            tr.bordes
              td #[strong Gamificación y realidad virtual]
              td Juegos educativos, simulaciones, aprendizaje inmersivo con realidad aumentada.
              td Google Expeditions ofrece viajes educativos en RV.

      .titulo-segundo.mb-5(data-aos="fade-up")#Seccion37
        h2 #[span 3.7] Entretenimiento y medios

      .row.mb-5
        .col-lg-8
          p La Inteligencia Artificial ha transformado la industria del entretenimiento y los medios, permitiendo experiencias personalizadas, automatización de procesos creativos y mejoras en la distribución de contenido; sus aplicaciones van desde sistemas de recomendación hasta generación de contenido con IA; esta tecnología está redefiniendo la manera en que consumimos entretenimiento. En la tabla 8 se muestran algunas de las aplicaciones en este campo.
        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/18.svg", alt="")

      .titulo-figura.mb-2
        h5 Tabla 8. 
        span Aplicaciones de la IA en el sector de entretenimiento y medios de comunicación

      .tabla-a.color-acento-contenido.mb-5
        table#Tabla8.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td Personalización de la experiencia del cliente
              td Sistemas de recomendación, optimización de interfaces, análisis de engagement.
              td Netflix y Spotify personalizan contenido con IA.
            tr.bordes
              td Publicidad digital y automatización de #[em marketing]
              td Generación de guiones, edición de video, deepfakes, música con IA.
              td OpenAI desarrolló Jukebox para crear música.
            tr.bordes
              td Optimización del comercio electrónico
              td Redacción automática, fact-checking, análisis de audiencia, traducción.
              td The Washington Post utiliza IA con Heliograf.
            tr.bordes
              td Logística y cadena de suministro inteligente
              td NPCs inteligentes, mundos procedurales, gráficos mejorados.
              td The Last of Us Part II, utiliza IA avanzada para mejorar la jugabilidad.
            tr.bordes
              td Análisis predictivo y comportamiento del consumidor
              td Algoritmos de recomendación, edición automática, #[em chatbots], moderación.
              td TikTok utiliza IA para recomendar videos.


      .titulo-segundo.mb-5(data-aos="fade-up")#Seccion38
        h2 #[span 3.8] Seguridad y ciberseguridad

      p La Inteligencia Artificial está cambiando la seguridad digital y física, permitiendo una detección de amenazas más rápida y eficaz, a continuación, se muestran sus principales aplicaciones.


      .titulo-figura.mb-2
        h5 Tabla 9. 
        span Aplicaciones de la IA en el sector de seguridad y ciberseguridad

      .tabla-a.color-acento-contenido.mb-5
        table#Tabla9.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Detección y prevención de ciberataques]
              td Identificación de #[em malware], detección de intrusos, análisis de comportamiento.
              td #[em Darktrace] detecta ciberataques en tiempo real.
            tr.bordes
              td #[strong Autenticación y protección de datos]
              td Reconocimiento biométrico, encriptación avanzada, monitoreo de accesos.
              td Apple Face ID utiliza IA para autenticación segura.
            tr.bordes
              td #[strong Prevención del fraude y seguridad financiera]
              td Análisis de transacciones, detección de fraudes, autenticación de usuarios.
              td PayPal bloquea transacciones fraudulentas con IA.
            tr.bordes
              td #[strong Seguridad física y vigilancia inteligente]
              td Reconocimiento facial, videovigilancia, #[em drones] de seguridad.
              td China utiliza IA para la vigilancia en aeropuertos.
            tr.bordes
              td #[strong Seguridad en infraestructuras críticas y redes]
              td Protección de redes industriales, seguridad en #[em IoT], predicción de ataques.
              td IBM Watson Security protege infraestructuras críticas.



      .titulo-segundo.mb-5(data-aos="fade-up")#Seccion39
        h2 #[span 3.9] Agricultura

      .row.mb-5
        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/19.png", data-aos="zoom-in")
        .col-lg-8
          p(data-aos="fade-left").mb-4 En comparación con otros sectores, la agricultura aún no está utilizando al máximo las aplicaciones potenciales de la Inteligencia Artificial, pues la aplicación de esta en el sector agrario, todavía está en fase de desarrollo mientras que, en otros sectores, ya es más visible su utilización. No obstante, cada vez son más las aplicaciones de la Inteligencia Artificial en la agricultura, lo que mejorará la gestión y eficiencia de toda la cadena, desde el trabajo del campo, hasta el análisis y utilización de la gran cantidad de datos que se generan.

      
          .bg-color-1.p-4(data-aos="fade-left").mb-4
            .row.align-items-start
              .col-lg-auto
                img(src="@/assets/curso/tema3/20.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 Un factor para destacar en el sector agrario, es que ha despertado el interés de los grandes gigantes informáticos, aprovechando su conocimiento en el desarrollo de la Inteligencia Artificial, unido a plataformas y aplicaciones digitales, que se encuentran en continuo desarrollo. 
      
          p(data-aos="fade-left").mb-4 Por otro lado, el uso de drones para la toma de datos en las explotaciones y cámaras infrarrojas y multiespectrales para la toma de imágenes de los cultivos, ha abierto nuevas oportunidades para el desarrollo de herramientas basadas en Inteligencia Artificial. En la siguiente tabla, se muestran las principales aplicaciones en este campo.
      
      .titulo-figura.mb-2
        h5 Tabla 10. 
        span Aplicaciones de la IA en el sector de la agricultura

      .tabla-a.color-acento-contenido.mb-5
        table#Tabla10.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Agricultura de precisión]
              td Análisis del suelo, #[em drones] para monitoreo, optimización de insumos.
              td John Deere utiliza IA para analizar la fertilidad del suelo.
            tr.bordes
              td #[strong Automatización y robótica agrícola]
              td Tractores autónomos, cosecha robotizada, #[em drones] para fumigación.
              td Blue River Technology optimiza el control de malezas con IA.
            tr.bordes
              td #[strong Optimización del uso del agua y riego inteligente]
              td Sensores de humedad, riego automatizado, análisis climático.
              td Netafim utiliza IA para ahorrar agua en el riego.
            tr.bordes
              td #[strong Detección de plagas y enfermedades]
              td Análisis de imágenes, modelos predictivos, aplicaciones móviles.
              td Plantix diagnostica enfermedades en cultivos, con IA.
            tr.bordes
              td #[strong Análisis predictivo y gestión de cosechas]
              td Predicción de rendimientos, optimización de cosecha, gestión logística.
              td IBM Watson anticipa la producción agrícola.



      .titulo-segundo.mb-5(data-aos="fade-up")#Seccion40
        h2 #[span 3.10] Ingeniería

      .row.mb-5
        .col-lg-8
          p La Inteligencia Artificial (IA) está cambiando la ingeniería en múltiples disciplinas, desde el diseño y la simulación, hasta la optimización de procesos y el mantenimiento predictivo. Gracias a los algoritmos avanzados, Machine Learning y robótica, la IA permite mejorar la precisión, eficiencia y seguridad en proyectos de ingeniería. A continuación, se relacionan algunas de estas aplicaciones en diferentes campos de la ingeniería.
        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/21.svg", alt="")

      .titulo-figura.mb-2
        h5 Tabla 11. 
        span Aplicaciones de la IA en la ingeniería


      .tabla-a.color-acento-contenido.mb-5
        table#Tabla11.bordes
          thead
            tr
              th.bg-color-tabla Área
              th.bg-color-tabla Aplicaciones de IA
              th.bg-color-tabla Ejemplo
          tbody.bg-color-4
            tr.bordes
              td #[strong Diseño y simulación en ingeniería]
              td Diseño generativo, simulaciones predictivas, análisis de impacto ambiental.
              td Autodesk utiliza IA para optimización de diseños.
            tr.bordes
              td #[strong Ingeniería civil y construcción]
              td Monitoreo con #[em drones], mantenimiento predictivo, construcción autónoma.
              td Boston Dynamics utiliza robots para inspección de obras.
            tr.bordes
              td #[strong Ingeniería industrial y manufactura]
              td Automatización de producción, mantenimiento predictivo, control inteligente.
              td Siemens optimiza fábricas con IA.
            tr.bordes
              td #[strong Ingeniería biomédica y salud]
              td Diseño de prótesis, análisis de imágenes médicas, simulaciones biológicas.
              td Zebra Medical Vision detecta enfermedades con IA.
            tr.bordes
              td #[strong Ingeniería energética y medioambiental]
              td #[em Smart grids], energías renovables, monitoreo ambiental, gestión de residuos.
              td Google DeepMind optimiza el consumo energético.
            tr.bordes
              td #[strong Ingeniería aeroespacial y automotriz]
              td Diseño optimizado, vehículos autónomos, mantenimiento predictivo.
              td Tesla implementa IA en la conducción autónoma.



      .bg-full-width.bg-color-3
        .px-4.px-md-5.py-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/22.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 En resumen, la Inteligencia Artificial se ha consolidado como una herramienta clave para la transformación digital, en múltiples sectores, impactando la eficiencia, la toma de decisiones y la innovación. Su integración ha permitido mejorar procesos, reducir costos y optimizar la gestión de recursos en áreas tan diversas como la salud, la educación, la industria, el comercio y la seguridad, entre otras.
      


      .bg-full-width.border-top.actividad.bg-color-actividad
        .p-4.p-md-5
          #Actividad                
            <Actividad :cuestionario="cuestionario"/>

      .bg-full-width.border-top.color-primario
        .p-4.p-md-5
          h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
          .row.material-complementario
            .col-12.col-md-6.col-lg-7
              p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
  
              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/57582" target="_blank" rel="noopener noreferrer") Benítez Iglésias, R. (2014). Inteligencia Artificial avanzada: ( ed.). Editorial UOC. 
  
            .col-12.col-md-6.col-lg-3.offset-lg-1
              figure
                img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              'El "invierno de la IA" se refiere a periodos en los que el entusiasmo y la inversión en IA disminuyeron.',
            tipo: 'opcion_unica',
            opciones: [
              { id: 'a', texto: 'Falso', esCorrecta: false },
              { id: 'b', texto: 'Verdadero', esCorrecta: true },
            ],
            mensaje_correcto:
              '¡Correcto! El "invierno de la IA" es un periodo de bajo entusiasmo e inversión.',
            mensaje_incorrecto: 'Revisa el concepto de "invierno de la IA".',
          },
          {
            id: 2,
            texto: 'La IA no tiene ninguna aplicación en la ciberseguridad.',
            tipo: 'opcion_unica',
            opciones: [
              { id: 'a', texto: 'Falso', esCorrecta: true },
              { id: 'b', texto: 'Verdadero', esCorrecta: false },
            ],
            mensaje_correcto:
              '¡Correcto! La IA tiene muchas aplicaciones en ciberseguridad.',
            mensaje_incorrecto:
              'Revisa las aplicaciones de la IA en ciberseguridad.',
          },
          {
            id: 3,
            texto:
              'El uso de IA en el diagnóstico médico es menos preciso que los métodos tradicionales.',
            tipo: 'opcion_unica',
            opciones: [
              { id: 'a', texto: 'Falso', esCorrecta: true },
              { id: 'b', texto: 'Verdadero', esCorrecta: false },
            ],
            mensaje_correcto:
              '¡Correcto! La IA puede ser más precisa que los métodos tradicionales.',
            mensaje_incorrecto:
              'Revisa los avances de la IA en diagnóstico médico.',
          },
          {
            id: 4,
            texto: '¿Cuál de estas afirmaciones sobre la IA es correcta?',
            tipo: 'opcion_unica',
            opciones: [
              {
                id: 'a',
                texto: 'La IA solo se usa en dispositivos móviles',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'La IA no tiene impacto en la educación',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'La IA es un concepto reciente del siglo XXI',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'La IA se usa en múltiples sectores, desde la salud hasta el entretenimiento',
                esCorrecta: true,
              },
            ],
            mensaje_correcto: '¡Correcto! La IA se usa en muchos sectores.',
            mensaje_incorrecto: 'Revisa los sectores de aplicación de la IA.',
          },
          {
            id: 5,
            texto:
              '¿Qué tipo de IA es puramente teórica y aún no ha sido desarrollada?',
            tipo: 'opcion_unica',
            opciones: [
              { id: 'a', texto: 'IA Débil', esCorrecta: false },
              { id: 'b', texto: 'IA General', esCorrecta: false },
              { id: 'c', texto: 'IA Superinteligente', esCorrecta: true },
              { id: 'd', texto: 'IA con Memoria Limitada', esCorrecta: false },
            ],
            mensaje_correcto: '¡Correcto! La IA Superinteligente es teórica.',
            mensaje_incorrecto: 'Revisa los tipos de IA.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
