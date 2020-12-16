<template>
  <div id="app">
    <!-- barra navegacion -->
    <image-text> </image-text> 
    <!-- Slice -->
    <slice></slice>
    <!-- Servicios -->
    <services-section> </services-section>
    <!-- noticias -->
    <div class="labelServicios">
        <p class="lead mb-0 labelnoticias" id="noticias">NOTICIAS</p>            
    </div>
    <NewsSection> </NewsSection>
    <!-- Equipo -->
    <div class="labelServicios">
             <p class="lead mb-0" id="nosotros">NOSOTROS</p>            
    </div>    
    <div class="container-fluid perfiles">
      <div  class="row mb-5">
        <div class="col mt-5" v-for="(miembro, index) of  Team" :key="index">

          <team-card :member="miembro" > </team-card>
        </div >
      </div> 
    </div>
    <!-- Footer --> 
    <footer-section> </footer-section>
  </div>
</template>


<script>
import ImageText from './components/ImageText.vue'
import ServicesSection from './components/ServicesSection.vue'
import FooterSection from './components/FooterSection.vue'
import TeamCard from './components/TeamCard.vue'
import Slice from './components/Slice.vue'
import NewsSection from './components/ApiNews.vue'


export default {
    name: 'App',
    components:{
        ImageText,
        Slice,
        ServicesSection,
        FooterSection,
        TeamCard,
        NewsSection,
  },
  data(){
     return{
        Team:[
            {             
              codigo: 1,
              nombre: 'Jhon  Jimenez',
              descripcion : "Ingeniero de sistemas especializado en el area de la gestion y administracion de redes y seguridad, preservacion y a aseguramiento de la informacion, en particular en el area del procesamiento sismico en sector petrolero ",
              rol: 'Desarrollador FRONT Y BACK ',	
              image : "https://i.imgur.com/qWIlWUo.jpg",
            },
            {
              codigo: 2,
              nombre: 'David Orjuela',
              descripcion : "Ingeniero químico con experiencia en asuntos regulatorios y trade compliance de sustancias químicas, agrícolas y farmacológicas. Con conocimientos en metodologías de diseño de aplicaciones y desarrollo web.",
              rol: 'Desarollador FRONT Y BACK',	
              image : "https://i.imgur.com/rhQ2l10.jpg",
            },	
            {
              codigo: 3,
              nombre: 'Fabio Gaviria',
              descripcion : "Ingeniero de Telecomunicaciones, tengo conocimiento en infraestructura y redes, y algo de desarrollo e Inteligencia artificial; trabajo como docente de matemáticas y desarrollo de software incentivando en los  jovenes ",
              rol: 'Desarrollador' ,	
              image : "https://i.imgur.com/ZeeQto2.jpg",
            },	
            {
              codigo: 4,
              nombre: 'Juan Carlos Marin',
              descripcion : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Numquam alias sapiente pariatur magnam fuga consequuntur molestias ducimus iure obcaecati quisquam. Possimus, quaerat provident minus aspernatur neque velit." ,
              rol: 'Desarrollador',	
              image : "https://i.imgur.com/WJBThH9.jpg",
            },	
            {
              codigo: 5,
              nombre: 'Willian Romero',
              descripcion : "Mi nombre es William Alberto Romero Ortega, tengo una amplia experiencia en el sector educativo público y privado, como docente y coodinador, aportando con los jovenes desde el campo educativo al desarrollo de las TI y comunicaciones en el país.",
              rol: 'Documentacion',	
              image : "https://i.imgur.com/tPYp5Jc.png",
            }
          ]
      }
    }      
}
</script>

<style scoped>
.body-cnt{ 
    max-width: 1200px;
    margin-left: auto;
    margin-right:auto;
    font-family: Tahoma, sans-serif;   
}

.perfiles{
background-color: rgb(25,153,159);

}

.labelServicios{
    background-color: rgb(108,117,125);  
    height: 30.98px;
    text-align: center;
    margin-top:5px;
    margin-bottom:5px
    
}
.labelnoticias{
    background-color: rgb(108,117,125);  
    height: 30.98px;
    margin-top: 5px;
    margin-bottom:5px
    
}

</style>