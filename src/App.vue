<template>
  <div id="app">
    <image-text> </image-text> 
    <services-section> </services-section>
    <footer-section> </footer-section>
  </div>
</template>



<script>
import ImageText from './components/ImageText.vue'
import ServicesSection from './components/ServicesSection.vue'
import FooterSection from './components/FooterSection.vue'


export default {
    name: 'App',
    components:{
       ImageText,
       ServicesSection,
       FooterSection,
  }
}
</script>
