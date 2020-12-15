<template>
 <!-- Image and text -->
     <nav class="navbar navbar-expand-lg navbar-light bg-light m navegador">                
        <div class="collapse navbar-collapse main-nav" id="navbarNav">
          <ul class="navbar-nav ">
              <li class="nav-item ">
                <img class="logo-petroseismic" src="../assets/logo2.png" alt="">
              </li>
          </ul>
          <ul class="navbar-nav ">  
            <li class="nav-item ">
              <a class="nav-link" >Inicio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#interpretacion">Servicios</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Noticias</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Equipo</a>
            </li>
          </ul>
        </div>
      </nav>
</template>

<script>
export default {
        name: "ImageText",        
    }
</script>

<style scoped>

 .navegador{    
    height: 64px;
    width: 1090px;
    background: rgb(25,153,159) 
 }

  .main-nav {
    display : flex;     
    display: -webkit-flex;    
    justify-content:space-between;
    list-style: none ;
    background: rgb(25,153,159) 
  }

  .main-nav .logo {
    background: rgb(25,153,159) ;
   
    height: 64px;
    }

  .logo-petroseismic{
    padding-top: 6.2px;
    padding-bottom: 6.2px;
    align-content: stretch  ;    
    margin-left: 15.35px;
    height: 51.6px;
    width: 123px;
  }


.main-nav ul{
    margin: 0;
    padding: 0;
    list-style: none;
}
.main-nav ul li{
    display: inline-block;
}

</style>
