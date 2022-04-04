<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span S
      h1 Diagnosticar sistemas de tratamiento
    p Este documento contiene todos los conceptos básicos necesarios para entender e identificar los sistemas de agua para el consumo humano, además se exponen características y tipos de hidráulica básica para el agua potable, así como la normatividad vigente que debe ser aplicada para su uso. Por lo que se proponen algunas figuras, documentos y, videos adicionales que son importantes y que complementan el tema abordado permitiendo tener mayor claridad de las diferentes redes y sistemas de alcantarillado, algunos esquemas de intervención, procedimientos y canales de información, tipos de tuberías y materiales y accesorios utilizados en sistemas de acueducto y alcantarillado. 

    p.mb-5 El objetivo principal de este componente es que el aprendiz pueda identificar los sistemas de agua para el consumo humano y compruebe el funcionamiento de estos de acuerdo con normas técnicas vigentes que deben adoptarse por todos los usuarios de dicho recurso hídrico, asimismo, es fundamental entender el papel que juega la política pública para el control de los riesgos que puede causar un funcionamiento inadecuado de estos sistemas de agua, estas entidades gubernamentales, deben adoptar lineamientos y planes de emergencia para el manejo de desastres asociados a la prestación de este servicio público domiciliario de acueducto, alcantarillado y aseo. 
    .row.justify-content-center
      .col-lg-12.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="alt")


</template>

<script>
export default {
  name: 'Sintesis',
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
