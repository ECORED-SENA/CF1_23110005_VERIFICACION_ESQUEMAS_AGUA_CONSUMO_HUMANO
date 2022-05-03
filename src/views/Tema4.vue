<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade")
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Diagnosticar sistemas de tratamiento
    p(data-aos="zoom-out") Es importante mencionar en este apartado, el gran crecimiento que han tenido las ciudades en los últimos años y con ello el gran crecimiento de los sistemas de alcantarillado, de aquí parte una necesidad clara de aplicar sistemas de tratamiento que velen por la salubridad de la población. En primer lugar, se puede realizar un tratamiento preliminar de las aguas residuales que las preparen para su adecuado tratamiento directamente del sistema de alcantarillado removiendo así todos los desperdicios o sólidos que puedan encontrarse en este y que puedan ser difícilmente reutilizados. 
    .row.justify-content-center(data-aos="zoom-out")
      .col-lg-4
        img(src='@/assets/curso/tema4/img1.png', alt='Texto que describa la imagen')

      .col-lg-8.mt-4
        p Dentro de estos sistemas de tratamiento <strong>está el primario, el cual se compone de un pretratamiento; encargado de efectuar un control del agua para depurarla; consiguiente está el tratamiento secundario, encargado de depurar las partículas que no se pudieron eliminar en el primer proceso y así realizar una desinfección eficiente de los residuos sólidos que quedan. En tercer lugar, está la línea de fangos, la cual realiza un proceso especial para espesar los fangos primarios y secundarios y recuperarlos para producir energía eléctrica o utilizarla como combustible de calefacción de edición.</strong> Ahora bien, se encuentra el desbaste, aquí se retiene la mayor cantidad de materias de un volumen específico que están presentes en el agua las cuales pueden ocasionar alteraciones negativas en los tratamientos de las aguas y los fangos si no son tratadas a tiempo, seguido de este, está el desarenado, el cual elimina los cuerpos flotantes más importantes como las grasas, las fibras, los pelos , entre otros y de la mano, está la decantación primaria el cual elimina a un bajo costo los flotantes restantes que se acumulan en grandes concentraciones y, por último, está el tratamiento biológico aerobio; encargado de la degradación de materia orgánica causa por los microorganismos del proceso (Rodríguez, s.f.). 

    .row.bg11.lag4
      .col-lg-4
      .col-lg-8
        p.mt-4 Veamos de manera gráfica cómo es el funcionamiento de las aguas residuales:

    .titulo-sexto.color-acento-contenido.mt-5(data-aos="zoom-out-up")
      h5 Figura 2
      span Sistemas de saneamiento
    img(data-aos="zoom-out-up")(src='@/assets/curso/tema4/img2.svg', alt='Texto que describa la imagen')

    .row.justify-content-center.mt-5.bg77(data-aos="zoom-out-up")

      .col-lg-4.ml
        img(src='@/assets/curso/tema4/img3.svg', alt='Texto que describa la imagen')
      .col-lg-6
        #t_9_9.titulo-segundo.color-acento-contenido.mt-4.mb-4
          h2 Tratamiento de aguas residuales
        p Si desea ampliar la temática relacionada con el tratamiento de aguas residuales, puede hacerlo a través del siguiente video: 
        a.boton.color-acento-botones.me-3(:href="('https://www.youtube.com/watch?v=ktxKQC4FWc8')" target="_blank" type="application/pdf")
          span Ver video
          i.fas.fa-file-download
    separador
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 4.1. Técnicas de recolección de información 
    p(data-aos="zoom-out-right") Las técnicas de recolección de información son métodos que sirven para relacionarse más a fondo con los participantes acerca de un tema específico y así, obtener información necesaria para alcanzar objetivos específicos. La mejor manera de adaptarse a los cambios del mercado y sus necesidades es a través de la gestión de la información, entender y saber qué es lo que los consumidores opinan y piensan de un producto o servicio hace que se implemente aún más en las empresas la investigación de mercado. Para dicha investigación, existen diferentes técnicas utilizadas que permiten conocer a profundidad un tema en general, estas pueden ser cualitativas, que permiten una compresión y profundidad alta de información, pero, no permiten una generalización de los resultados. Y, por otra parte, están las herramientas cuantitativas, las cuales, a diferencia de las anteriores, permiten un análisis de grandes cantidades numéricas o de cifras representativas que logran cuantificar los resultados (Research Integrity, s.f.).
    p Veamos, a continuación, en el siguiente recurso las técnicas más utilizadas:
    .titulo-sexto.color-acento-contenido
      h5 Figura 2
      span Sistemas de saneamiento
    .row.justify-content-center.bg4(data-aos="zoom-out-right")
      .col-lg-7
        img(src='@/assets/curso/tema4/img4.svg', alt='Texto que describa la imagen')
    separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 4.2. Tipos de planos y esquemas para definir sistemas alternativos
    p Esquematizar es una herramienta indispensable que proporciona al estudiante una visión completa y estructurada de un tema específico de estudio, es importante que su estructura sea de forma lógica y jerarquizada que demuestre la integración de cada idea con las demás; logrando así resumir en gran medida un contenido de manera sencilla y clara. Además, cabe resaltar que los esquemas pueden servir como sistemas alternativos para plasmar ideas de manera más visual, ofreciendo un desarrollo de las capacidades de análisis, síntesis, orden lógico y dominio de temas, asimismo, facilitan la memorización y el aprendizaje debido a que a muchas personas les resulta mucho más fácil poder memorizar imágenes, colores, símbolos o ciertos patrones dentro de los esquemas. 
    p Existen diferentes tipos de esquemas que pueden implementarse dependiendo de cómo y qué se quiera expresar; veámoslos:
    .row.mb-5
      .col-sm-6.col-lg-3.mb-4.mb-lg-0

        .tarjeta--boton.bg98.p-4
          <br>
          .row.mb-3.mt-1
            .col-2
              figure
                img(src='@/assets/curso/tema4/ico1.svg', alt='Texto que describa la imagen')

          h3 Esquema de numeración de ideas
          p Este esquema puede desarrollarse por nivel de importancia y así mismo asignarle la numeración correspondiente (1.1,1.2,1.3…)
          <br><br>
          .row
            .col-auto
              a.boton.color-acento-botonones.indicador__container(@click="modal1 = true")
                span <strong>Ver ejemplo</strong>
                .indicador--click(v-if="mostrarIndicador")
            .col
                a.lnk(@click="modal1 = false") 
          
          ModalA(:abrir-modal.sync="modal1")
            .row.align-items-center
              .col-md-12.mb-4.mb-md-0
                img(src='@/assets/curso/tema4/img5.svg', alt='Texto que describa la imagen')
          
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.bg98.p-4
          <br>
          .row.mb-3
            .col-2.alli
              figure
                img(src='@/assets/curso/tema4/ico2.svg', alt='Texto que describa la imagen')

          h3 Esquema de llaves
          p.mb-1 Este esquema consiste en un modelo que integra mucho más las ideas mediante flechas, barras o llaves con el fin de sintetizar cualquier tipo de información, este puede ser de manera vertical o horizontal.
          <br>
          .row.mb-1.mt-2
            .col-auto
              a.boton.color-acento-botonones.indicador__container(@click="modal2 = true")
                span <strong>Ver ejemplo</strong>
            .col
                a.lnk(@click="modal2 = true") 
          
          ModalA(:abrir-modal.sync="modal2")
            .row.align-items-center
              .col-md-12.mb-4.mb-md-0
                img(src='@/assets/curso/tema4/img6.svg', alt='Texto que describa la imagen')
          
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.bg98.p-4
          .row.mb-3.mt-3
            .col-4.alli
              figure
                img(src='@/assets/curso/tema4/ico3.svg', alt='Texto que describa la imagen')

          h3 Esquema radial
          p.mb-1 Este esquema consiste en que la idea principal comienza en el centro y de allí se despliegan las ideas secundarias y complementarias.
          <br><br><br>
          .row.mb-2.mt-2
            .col-auto
              a.boton.color-acento-botonones.indicador__container(@click="modal3 = true")
                span <strong>Ver ejemplo</strong>
            .col
                a.lnk(@click="modal3 = true") 
          
          ModalA(:abrir-modal.sync="modal3")
            .row.align-items-center
              .col-md-12.mb-4.mb-md-0
                img(src='@/assets/curso/tema4/img7.svg', alt='Texto que describa la imagen')
          

      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.bg98.p-4
          .row.mb-3.mt-3.awww
            .col-4.alli
              figure
                img(src='@/assets/curso/tema4/ico4.svg', alt='Texto que describa la imagen')

          h3 Diagrama de flujo
          p.mb-1 Este esquema consiste en resumir una idea de manera muy visual mientras se responden preguntas en el interior de este.
          <br><br><br><br>
          .row.mb-2.mt-2
            .col-auto
              a.boton.color-acento-botonones.indicador__container(@click="modal4 = true")
                span <strong>Ver ejemplo</strong>
            .col
                a.lnk(@click="modal4 = true") 
          
          ModalA(:abrir-modal.sync="modal4")
            .row.align-items-center
              .col-md-12.mb-4.mb-md-0
                img(src='@/assets/curso/tema4/img8.svg', alt='Texto que describa la imagen')
    p Podemos encontrar líneas de tiempo para resumir textos históricos y plasmarlos en una secuencia y, por último, encontramos los mapas conceptuales, los cuales dan importancia a la relación entre los conceptos de manera más jerarquizada y organizada.
    p Para realizar un buen esquema, se recomienda:          
    .row.bgxx.p-5.justify-content-center
      .col-1
        img.wiaz(src='@/assets/curso/tema4/1.svg', alt='Texto que describa la imagen')
        img.wiaz.mt-1(src='@/assets/curso/tema4/2.svg', alt='Texto que describa la imagen')
        img.wiaz.mt-1(src='@/assets/curso/tema4/3.svg', alt='Texto que describa la imagen')
        img.wiaz.mt-1(src='@/assets/curso/tema4/4.svg', alt='Texto que describa la imagen')
        img.wiaz.mt-1(src='@/assets/curso/tema4/5.svg', alt='Texto que describa la imagen')
        img.wiaz.mt-1(src='@/assets/curso/tema4/6.svg', alt='Texto que describa la imagen')
      .col-10
        p.mt-4 Realizar una <strong>lectura detallada</strong> y analítica del tema.
        p.mt-4 <strong>Subrayar los temas</strong> que más encuentre relevantes en el texto.
        p.mt-4 Hacer uso de <strong>palabras clave</strong> o frases cortas que puedan entenderse fácilmente.
        p.mt-4 Elegir el tipo de <strong>esquema que más se adecue</strong> a las ideas planteadas.
        p.mt-4 Extraer las <strong>ideas</strong> secundarias.
        p.mt-4 Seleccionar <strong>otros conceptos</strong> subordinados a las ideas secundarias.
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema4',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    mostrarIndicador: true,
    indicadorImagenZoom: true,
    indicadorTarjetaFlip: true,
    indicadorTarjetaSlide: true,
    modal1: false,
    modal2: false,
    modal3: false,
    modal4: false,

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
