<template>

    <!-- Footer -->
<footer class="page-footer bg-secondary text-white pt-4 pie">

      <!-- Footer -->
<footer class="page-footer font-small mdb-color pt-4 seccion-footer" >

  <!-- Footer Links -->
  <div class="container text-center text-md-left">

    <!-- Footer links -->
    <div class="row text-center text-md-left mt-3 pb-3">

      <!-- Grid column -->
      <div class="col-md-3 col-lg-3 col-xl-3 mx-auto mt-3">
        <h6 class="text-uppercase mb-1 font-weight-bold" >Quienes somos </h6>
        <p font >Somos una empresa Colombiana fundada en el 2002, contamos con profesionales altamente calificados en la generacion  de datos geofísicos
             que permiten obtener soluciones e interpretaciones más coherentes del suelo y subsuelo en diferentes disciplinas .</p>
      </div>
      <!-- Grid column -->

      <hr class="w-100 clearfix d-md-none">

      <!-- Grid column -->
      <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mt-3">
        <h6 class="text-uppercase mb-1 font-weight-bold">Productos</h6>
        <p>
          <a href="#interpretacion">Interpretacion</a>
        </p>
        <p>
          <a href="#procesamiento">Procesamiento</a>
        </p>
        <p>
          <a href="#adquisicion">Adquisicion</a>
        </p>
        
      </div>
      <!-- Grid column -->

      <hr class="w-100 clearfix d-md-none">

      <!-- Grid column -->
      <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mt-3">
        <h6 class="text-uppercase mb-1 font-weight-bold">Equipo</h6>
        <p>
          <a href="mailto:dafel9809@hotmail.com" >David Orjuela</a>
        </p>
        <p>
          <a href="mailto:jej.mail@gmail.com" >Jhon Jimenez</a>
        </p>
        <p>
          <a href="mailto:fabio.gaviria@gmail.com" >Fabio Gaviria</a>
        </p>
        <p>
          <a href="mailto:juanmarin.gz99@gmail.com" >Juan Marin</a>
        </p>
        <p>
          <a href="mailto:romero02@gmail.com" >Willian romero</a>
        </p>
      </div>

      <!-- Grid column -->
      <hr class="w-100 clearfix d-md-none">

      <!-- Grid column -->
      <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mt-3">
        <h6 class="text-uppercase mb-1 font-weight-bold">Contacto</h6>
        <p>
          <i class=""></i>Bogota calle 104 19-20 Col</p>
        <p>
           <a href="mailto:contacto@petroseismicservices.co" > contacto@petroseismicservices.co</a> 
        <p>
          <i class=""></i> + 571 2575655</p>
         
        <p>
          <i class=""></i> + 571 2575636</p>
      </div>
      <!-- Grid column -->

    </div>
    <!-- Footer links -->

    <hr>

    <!-- Grid row -->
    <div class="row d-flex align-items-center">

      <!-- Grid column -->
      <div class="col-md-7 col-lg-8">

        <!--Copyright-->
        <p class="text-center text-md-left">© 2020 Copyright:
          <a href="https://www.misiontic2022.gov.co/portal/">
            <strong> MisionTIC2022 Ciclo3</strong>
          </a>
        </p>

      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      

        <!-- Social buttons -->
        
      <div class="d-flex flex-column align-items-center ">
        <h4 class="mb-4">Siguenos en</h4>
        
        <ul >
            <div class="d-flex flex-row bd-highlight mb-3" >   
        
            <li><a href="https://www.facebook.com/"><span class="social-icon social-facebook"><i class="fa fa-facebook"></i></span> </a></li>
            <li><a href="https://www.google.com/"><span class="social-icon social-google"><i class="fa fa-google"></i></span></a></li>
            <li><a href="https://www.linkedin.com/"><span class="social-icon social-linkedin"><i class="fa fa-linkedin"></i></span></a></li>
            <li><a href="https://www.instagram.com/"><span class="social-icon social-instagram"><i class="fa fa-instagram"></i></span></a></li>
            <li><a href="https://twitter.com/"><span class="social-icon social-twitter"><i class="fa fa-twitter"></i></span></a></li>
            </div>
        </ul>
        
       </div>
      
    </div>
  </div>
</footer>


</footer>
<!-- Footer -->
</template>



<script>
export default {
    name: 'FooterSection'
}
</script>

<style scoped>
.pie{
width: 1080px;

}

.iconos {

    background-color: #eee;
    font-family: "Poppins", sans-serif;
    font-weight: 300;
    height: 100vh;
    display: flex;        
}

.social-icon {
    height: 70px;
    width: 70px;
    display: flex;    
    justify-content: center;
    align-items: center;
    color: #fff;
    font-size: 27px;
    text-align: center;
    margin-right: 11px;
    cursor: pointer;
    list-style:none;
    
}

.social-twitter {
    background-color: #55acee
}

.social-facebook {
    background-color: #3b5999
}

.social-linkedin {
    background-color: #0077B5
}

.social-google {
    background-color: #dd4b39
}

.social-instagram {
    background-color: #dd4b39
}

.social-icon i {
    transition: 0.4s all
}

.social-icon:hover i {
    transform: scale(1.4)
}

li{
list-style: none;


}
</style>
