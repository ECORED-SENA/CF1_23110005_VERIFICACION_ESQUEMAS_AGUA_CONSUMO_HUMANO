<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Procedimientos y canales de información
    p El objetivo principal de los procesos que involucran el tratamiento de aguas residuales se basa en la recuperación del recurso hídrico en su máximo nivel; el cual ha sido contaminado debido al aprovechamiento humano y busca su purificación para poder ser usada nuevamente. Para lograr remover todos los sólidos intratables de un sistema de alcantarillado se pueden emplear diferentes procedimientos como:
    <br><br><br>
    ImagenInfografica.color-acento-botones.mb-5.mt-4
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema3/img1.svg', alt='Texto que describa la imagen')

      .tarjeta.color-acento-botones.p-3(x="5%" y="7%" numero="")
        .h5.mb-2 1.
        p <strong>La separación de los desechos grandes:</strong> esta, se implementa para la purificación del agua retirando todos los sólidos que puedan obstruir el proceso.

      .tarjeta.color-acento-botones.p-3(x="19%" y="50%" numero="")
        .h5.mb-2 2.
        p <strong>La filtración de arena y aceite:</strong>en este proceso se hace una filtración mucho más minuciosa con el objetivo de retirar partículas mucho más pequeñas logrando separar incluso aceites o grasas durante el proceso. 
      .tarjeta.color-acento-botones.p-3(x="32%" y="7%" numero="")
        .h5.mb-2 3.
        p <strong>Clarificación del agua:</strong> después del filtrado, el agua llega a los tanques clasificadores primarios, los cuales permiten que el lodo llegue hasta el fondo y sean bombeados al exterior, permitiendo una mayor fluidez del agua.
      .tarjeta.color-acento-botones.p-3(x="46.7%" y="50%" numero="")
        .h5.mb-2 4.
        p <strong>Aireación:</strong> en esta etapa se bombea aire al tanque con el fin de propagar el crecimiento de las bacterias y acelerar así la degradación de materia orgánica.
      .tarjeta.color-acento-botones.p-3(x="60%" y="7%" numero="")
        .h5.mb-2 5.
        p <strong>Cloración o desinfección:</strong> ahora bien, este proceso tiene la finalidad de acabar cualquier tipo de bacteria presente en el agua, agregando cloro u ozono. 
      .tarjeta.color-acento-botones.p-3(x="74%" y="50%" numero="")
        .h5.mb-2 6.
        p <strong>Análisis y pruebas:</strong>  en esta etapa, se controlan criterios como específicos con el fin de verificar que el agua cumpla con todos los niveles requeridos. 
      .tarjeta.color-acento-botones.p-3(x="87%" y="7%" numero="")
        .h5.mb-2 7.
        p <strong>Tratamiento de lodos:</strong>  se obtiene una masa sólida durante el tratamiento con el fin de aprovecharla como fertilizante en siembras agrícolas.
    <br><br>
    #t_3_1.titulo-segundo.color-acento-contenido.mt-4
      h2 3.1. Conceptos, tipos y características de tubería basado en manuales técnicos
    p Para toda actividad relacionada con la conducción de aguas a través de tuberías se deben identificar qué tipos de tuberías emplear para el uso de agua potable y residual, por ejemplo: hace algunos años el material que se empleaba en dichos conductos para el agua potable era el hierro y el plomo, sin embargo, esto causaba grandes afectaciones en el agua llegando a contaminarla totalmente. Por lo anterior, actualmente se deben emplear sistemas de tubería con materiales como plástico o sus derivados.
    p A continuación, se pueden evidenciar los distintos tipos de tubería y su uso:        
    <br><br><br>
    .row.justify-content-center.bg4
      .col-lg-8

        LineaTiempoD.color-primario
          .row(numero="1" titulo="Tubería de hierro")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p Se utiliza usualmente para redes contra incendios y climatización.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img1.png', alt='Texto que describa la imagen')

          
          .row(numero="2" titulo="Tubería de acero inoxidable")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p Son empleadas para sistemas de fontanería como calefacción.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img2.png', alt='Texto que describa la imagen')

          .row(numero="3" titulo="Tubería polietileno reticulado")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br>
              p Son útiles tanto para fontanería como para calefacción, ya que cuentan con condiciones de flexibilidad y memoria térmica, se utilizan usualmente en sistemas de riego, casas rurales, entre otros.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img3.png', alt='Texto que describa la imagen')

          .row(numero="4" titulo="Tubería de cobre")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p Su uso más frecuente es en instalaciones de calefacción, agua potable y gas.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img4.png', alt='Texto que describa la imagen')

          .row(numero="5" titulo="Tubería PVC")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p Esta es empleada en redes de desagües para aguas potables, fecales o pluviales.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img5.png', alt='Texto que describa la imagen')

          .row(numero="6" titulo="Tubería PB")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p Este tipo de tubería es muy común y se usan para pequeñas reformas por su fácil manejo.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img6.png', alt='Texto que describa la imagen')
          .row(numero="7" titulo="Tubería de polipropileno")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p  Estas son las más recomendadas para la conducción de agua potable, es muy utilizada en hospitales, gimnasios, colegios, entre otros. 
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img7.png', alt='Texto que describa la imagen')
          .row(numero="8" titulo="Tubería multiplicada")
            .col-md-1
            .col-md-5.mb-4.mb-md-0.mt-2
              <br><br>
              p  Actualmente este es el tipo de tubería que más ha avanzado en cuanto a su uso, soporta grandes temperaturas y presiones. 
            .col-md-6
              figure
                img(src='@/assets/curso/tema3/img8.png', alt='Texto que describa la imagen')
        
        
        <br><br><br><br><br><br>
      p De acuerdo a lo anterior, se pueden evidenciar en diferentes manuales, la identificación de cada uno de los tipos de tubería existentes y allí mismo, se pueden encontrar aspectos como: descubrimiento, propiedades, ventajas y desventajas que puede ofrecer cada uno dependiendo su uso, algunas recomendaciones de uso, características específicas de dimensiones o presión, entre otros. 
      .row.justify-content-center
        .col-lg-1
        .col-lg-2
          img(src='@/assets/curso/tema3/ico1.svg', alt='Texto que describa la imagen')
        .col-lg-8
          .cajon.color-acento-botones.p-4.mb-4
            p Es muy valioso y de gran provecho que estos manuales den recomendaciones para aplicar los diferentes tipos de tuberías, según servicios de agua subterráneas, de distribución, de conductos de agua refrigerados, de drenaje y ventilación, calefacción, contra incendios, etc., es importante sacar provecho de estas herramientas ya que la mayoría de veces pasamos por alto las recomendaciones o instrucciones de cualquier manual sin fijarnos realmente la importancia que estos tienen para la aplicación de un proceso o el desarrollo de una tarea. 
    #t_3_2.titulo-segundo.color-acento-contenido.mt-4
      h2 3.2. Materiales y accesorios de sistemas de acueducto y alcantarillado
    p Retroalimentando cada aspecto de este tema, <strong>es fundamental identificar qué materiales y accesorios se necesitan para la implementación de un acueducto o alcantarillado,</strong> estos sistemas requieren claramente de materiales y accesorios específicos que sean efectivos y de gran duración, ya que de esto depende que el sistema también funcione de manera óptima.
    .row.justify-content-center
      .col-lg-8
        p Expuesto lo anterior, las tuberías que son para el manejo de agua potable son específicamente fabricadas en polietileno debido a que este material es mucho más flexible y seguro para la salud y así mismo, para la conducción del agua potable, por tanto, las redes de acueducto se fabrican de esta manera, con referencias de 16mm hasta 800mm que atienden perfectamente las necesidades de los usuarios desde la aducción hasta las conexiones domiciliarias. Asimismo, el sistema de alcantarillado interno consta de accesorios específicos como codos, tees y acoplamientos, algunos de estos pueden tener uno o más enchufes para poder combinar partes diferentes de la tubería, igualmente pueden ser necesarios otros elementos como la reducción; que permita una transición segura del alcantarillado a otras secciones y permite la articulación de hierro fundido y plástico. Por otro lado, está el cruce de planos, travesaño y la retracción, que permiten formar ramas en ángulos de 45 y 90 grados y 30, 40 y 60 para la colocación de tuberías paralelas.
        p <strong>Otro elemento usual en los sistemas de alcantarillado es el aireador o la válvula de alcantarillado,</strong> que sirve para bloquear la salida de gases al baño a través del inodoro y pueden ser también utilizados para la instalación de aguas residuales externas con el fin de bloquear el reverso del fluido circulante. 
      .col-lg-4
          img(src='@/assets/curso/tema3/img9.png', alt='Texto que describa la imagen')
    p.mt-4 Por último, existen diferentes tipos de materiales implementados en las tuberías <strong>como hierro fundido, polietileno, polipropileno, cloruro de polivinilo, acero, cemento de asbesto y cerámica,</strong> de estos elementos, los más utilizados son el polipropileno, polietileno y PVC ya que son más duraderos a diferencia del metal. Sin embargo, hay que prestar especial atención a las recomendaciones que los manuales puedan darnos ya que, el uso de estos materiales cambia dependiendo de su implementación (TechnoLux, s,f). 
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
