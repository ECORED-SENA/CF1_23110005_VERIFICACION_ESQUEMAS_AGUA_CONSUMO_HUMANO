<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Identificación de sistemas de agua para consumo humano 
    .row.justify-content-center(data-aos="zoom-in-left")
      .col-lg-4
        img.imgposition(src='@/assets/curso/tema1/img1.png', alt='Texto que describa la imagen')
      .col-lg-8
        p.mt-4 Para realizar una identificación adecuada de los sistemas de agua para el consumo humano, se debe, primeramente, tener claridad acerca de los conceptos básicos que están directamente relacionados con este proceso, para así, tener mayor claridad y apropiación de los términos a lo largo del desarrollo de la guía. Por lo anterior, este apartado expone diferentes conceptos básicos y algunas características y tipos de hidráulica básica para agua potable, los cuales ayudarán al fortalecimiento y reconocimiento de los diferentes sistemas de agua. 
        <br>
    .row.lag
      .col-lg-3
      .col-lg-9.bg1
        p.mt-3.maq Ahora bien, es fundamental entender que el agua es un recurso vital para la vida de toda una población e incluso de los ecosistemas, la calidad del agua determina aspectos sumamente importantes para la seguridad humana y la salud de nuestros recursos naturales, es por lo anterior, que todo el proceso que implica la obtención de agua potable debe ser responsable y con altos estándares de calidad, desde su recolección o captación hasta su distribución final. Los sistemas convencionales de abastecimiento de agua utilizan aguas superficiales; las cuales hacen referencia a fuentes visibles como lagos, ríos, arroyos o lagunas y también, utilizan aguas subterráneas, es decir, aquellas que se encuentran confinadas en el subsuelo como pozos o galerías filtrantes.
        
    <br><br>
    .row.mt-2(data-aos="zoom-out-right")
      .col-lg-8
        p Así mismo, un sistema de agua potable se proyecta con el fin de suministrar una cantidad suficiente de agua, con presión y calidad adecuada desde la fuente de suministro hasta los consumidores y para ellos, emplea elementos como tuberías, válvulas, hidrantes, almacenamiento, medidores, entre otros. De igual forma, se debe tener en cuenta que la recolección de muchas de estas aguas para el suministro humano, implican un proceso continuo de purificación para su consumo doméstico, el mantenimiento y tratamiento de los conductos de agua debe ser también indispensable en este proceso ya que, las tuberías son fuentes de alto riesgo de contaminación y esto puede llegar a afectar la distribución del recurso.
      .col-lg-4.mt-2
        img(src='@/assets/curso/tema1/img2.png', alt='Texto que describa la imagen')
    <br><br><br>
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-up")
      h2 1.1. Conceptos básicos
    p Un sistema de agua potable es el conjunto de instalaciones y equipos utilizados para el abastecimiento del agua en una población; cumpliendo siempre con criterios de continuidad, cantidades suficiente, calidad y presión necesaria para garantizar un servicio de agua óptimo a los miembros de una comunidad. 
    p De igual forma, todo el conjunto de tuberías, instalaciones y accesorios están destinados a llevar, tratar, almacenar y distribuir el agua desde su fuente hasta los hogares de dichas personas, cubriendo así una de las necesidades de la población. Así mismo, se tienen diferentes sistemas de agua potable como: sistema natural de desagüe, sistema de captación de agua lluvia, agua superficial, aguas subterráneas y acuífero (Velázquez, 2015)
    p El abastecimiento del agua para uso doméstico comprende las siguientes fases:

    .row.justify-content-center.bg2.mt-4(data-aos="zoom-in-up")
      .col-lg-2
        h3.mb-2.mt-2 ABASTECIMIENTO
    .row.mb-5.mt-3.justify-content-center(data-aos="zoom-in-down")
      .col-sm-6.col-lg-2.mb-4.mb-lg-0.wi1


        .tarjeta--boton.p-4.bg3
          .row.justify-content-center.mb-4
            .col-5
              figure
                img(src='@/assets/curso/tema1/ico1.svg', alt='Texto que describa la imagen')
          h3.text-center.abba.mt-2 Captación
          p.text-small.text-center.mb-3 Cuencas hidrográficas, ríos y quebradas
          
      .col-sm-6.col-lg-2.mb-4.mb-lg-0.wi1


        .tarjeta--boton.p-4.bg3
          .row.justify-content-center
            .col-5.mt-2
              figure
                img.mt-2(src='@/assets/curso/tema1/ico2.svg', alt='Texto que describa la imagen')
          h3.text-center.mt-4 Distribución
          p.text-small.text-center Túneles y tuberías
          <br>
      .col-sm-6.col-lg-2.mb-4.mb-lg-0.wi1


        .tarjeta--boton.p-4.bg3
          .row.justify-content-center.mb-1
            .col-5.mt-3
              figure
                img(src='@/assets/curso/tema1/ico3.svg', alt='Texto que describa la imagen')
          h3.text-center.mt-4 Almacenamiento
          p.text-small.text-center Embalses
          <br>
      .col-sm-6.col-lg-2.mb-4.mb-lg-0.wi1


        .tarjeta--boton.p-4.bg3
          .row.justify-content-center.mb-1
            .col-5.mt-3
              figure
                img(src='@/assets/curso/tema1/ico4.svg', alt='Texto que describa la imagen')
          h3.text-center.mt-4 Distribución
          p.text-small.text-center Túneles y tuberías
          <br>
      .col-sm-6.col-lg-2.mb-4.mb-lg-0.wi1


        .tarjeta--boton.p-4.bg3
          .row.justify-content-center.mb-0
            .col-5.mt-3
              figure
                img(src='@/assets/curso/tema1/ico5.svg', alt='Texto que describa la imagen')
          h3.text-center.mt-4 Producción
          p.text-small.text-center.mb-0 Planta de tratamiento (No convencional - Filtración directa)
    
    
    p Ahora hablaremos de diferentes sistemas y conceptos involucrados en el proceso de abastecimiento:
    TabsB.color-acento-contenido.mb-5(data-aos="zoom-out-left")
      .py-4.py-md-5(titulo="Hidráulica" :icono="require('@/assets/curso/tema1/ico6.svg')")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            <br>
            h4.mt-4 Hidráulica
            p.mt-2 El concepto de hidráulica hace alusión a un método tecnológico que emplea la circulación de un fluido, en este caso del agua, por medio de una tubería circular que sirve de medio para la transmisión de energía necesaria para su movimiento y/o funcionamiento, es decir, que esta energía aprovecha la fuerza del agua para mover turbinas a través de un generador.
        
          .col-md-5
            figure
              img(src='@/assets/curso/tema1/img3.svg', alt='Texto que describa la imagen')
          .col-md-1
      .py-4.py-md-5(titulo="Saneamiento" :icono="require('@/assets/curso/tema1/ico7.svg')")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            <br>
            h4.mt-4 Saneamiento
            p.mt-2 Para este caso, el saneamiento es aquel proceso encargado de recoger, transportar y realizar el tratamiento correspondiente de agua previendo los efectos negativos que puedan presentarse, es importante recalcar que tener acceso a un saneamiento adecuado, en este caso al agua potable, es fundamental para la salud pública y ambiental, por ello la responsabilidad que se tenga de las aguas residuales, los residuos orgánicos y alimenticios son de vital importancia para cumplir estándares de calidad en el recurso hídrico y también de las condiciones de vida urbana y rural. 
        
          .col-md-5
            figure
              img(src='@/assets/curso/tema1/img4.svg', alt='Texto que describa la imagen')
          .col-md-1
      .py-4.py-md-5(titulo="Sistemas de tratamiento" :icono="require('@/assets/curso/tema1/ico8.svg')")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            h4 Sistemas de tratamiento
            p.mt-2 Un sistema de tratamiento de aguas es aquel conjunto de procesos que se realizan para obtener una transformación en las propiedades del agua, especialmente de las negativas, con el fin de conseguir la calidad deseada de dicho recurso. Este proceso puede emplearse para agua residual, doméstica y no doméstica, potable purificado o incluso agua lluvia. 
            p Además, de lo mencionado con anterioridad, es importante identificar las características que debe tener el agua para el consumo humano, ya que aspectos físicos químicos y microbiológicos pueden llegar a afectar  directa o indirectamente a la población, estos criterios, como ya se indicó, serán determinados en gran parte por los Ministerios de Protección Social y de Ambiente, Vivienda y Desarrollo Territorial, asimismo, estos definieron los elementos adversos que puedan llegar a tener el mal uso o tratamiento del agua en la salud humana y, así mismo definieron las medidas preventivas a tomar para mitigar dichos impactos (Gobierno de Colombia, s.f.). 
        
          .col-md-5
            figure
              img(src='@/assets/curso/tema1/img5.svg', alt='Texto que describa la imagen')
          .col-md-1
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-out-left")
      h2 1.2. Características y tipos de hidráulica básica para agua potable
    .row.justify-content-center(data-aos="zoom-out-right")
        .col-lg-4
          img.imgposition(src='@/assets/curso/tema1/img6.png', alt='Texto que describa la imagen')
        .col-lg-8.mt-4
          p.mt-4 La hidráulica, tiene como objetivo la prevención de las enfermedades de tipo hídrico, desde su recolección del agua residual hasta su distribución, el buen manejo de este proceso da como resultado que los sistemas de agua potable y alcantarillado sanitario sean complementarios. Entre sus características están: el volumen; la presión y la densidad.
    .row.lag
      .col-lg-3
      .col-lg-9.bg1
        p.mt-3.maq Así mismo, la captación es la parte inicial del sistema hidráulico y, es aquí donde se recoge la cantidad de agua necesaria para poder abastecer a la población. <strong>En segundo lugar, está la conducción que es conformada por estructuras civiles y electromecánicas que llevan el agua a una planta de tratamiento y, allí, se implementan procesos que pueden ser químicos, físicos y/o mecánicos, los cuales permiten que el agua adquiera características aptas para el consumo humano y se tenga una adecuada regularización.</strong> El siguiente paso son las líneas de alimentación las cuales son el conjunto de tuberías que sirven como conducto del agua desde el tanque de regularización hasta la red de distribución, y en esta, se entrega el agua en condiciones de calidad a cada uno de los usuarios en sus hogares o domicilios.
    
    <br><br>
    p Ahora bien, están los sistemas de alcantarillado que tienen como objetivo el retiro de las aguas que han sido ya aprovechadas y por tanto, contaminadas por parte de los usuarios; consiguiente, está la red de atarjeas que son los conductos de menor diámetro que reciben las aguas residuales y salen de los hogares como descargas domiciliarias y, por último, está de nuevo el tratamiento; encargado de evitar la contaminación provocado por las aguas residuales. 
    p Sabiendo lo anterior, es importante que conozca a través del siguiente recurso, todos los pasos del proceso de la hidráulica, para entregar el agua en condiciones de calidad a los usuarios:          
    img(src='@/assets/curso/tema1/img7.svg', alt='Texto que describa la imagen')

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
