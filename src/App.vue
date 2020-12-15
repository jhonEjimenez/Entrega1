<template>
  <div id="app">
    <image-text> </image-text> 
    <services-section> </services-section>



    <div class="container-fluid">
      <div class="row justify-content-center mb-5">
        <team-card> </team-card>
      </div> 
    </div>
    
    <footer-section> </footer-section>
  </div>
</template>



<script>
import ImageText from './components/ImageText.vue'
import ServicesSection from './components/ServicesSection.vue'
import FooterSection from './components/FooterSection.vue'
import TeamCard from './components/TeamCard.vue'


export default {
    name: 'App',
    components:{
       ImageText,
       ServicesSection,
       FooterSection,
        TeamCard,
  },
  data(){
     return{
        Team:[
            {             
            codigo: 1,
            nombre: 'jhon',
            descripcion : " tesxto dedescripcion ",
            rol: 'desarollador all',	
            image : "../asset/image.jpg",
            },
            {
            codigo: 2,
            nombre: 'jhon2',
            descripcion : " tesxto dedescripcion ",
            rol: 'desarollador all',	
            image : "../asset/image.jpg",
            },	
                  {
            codigo: 3,
            nombre: 'jhon3',
            descripcion : " tesxto dedescripcion ",
            rol: 'desarollador all',	
            image : "../asset/image.jpg",
            },	
            {
            codigo: 4,
            nombre: 'jhon5',
            descripcion : " tesxto dedescripcion ",
            rol: 'desarollador all',	
            image : "../asset/image.jpg",
            },	
            {
            codigo: 5,
            nombre: 'jhon5',
            descripcion : " tesxto dedescripcion ",
            rol: 'desarollador all',	
            image : "../asset/image.jpg",
            },	
            ]
      }
    }
      
}
</script>
