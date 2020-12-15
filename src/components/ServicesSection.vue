<template>
    <!-- services -->
<div class="features-icons bg-light text-center servicios">
        <div class="labelServicios">
             <p class="lead mb-0">Servicios</p>            
        </div>
      <div class="container contenedor-imagen">        
        <div class="row">
          <div class="col-lg-4 ">
            <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3 ">
              <div class="features-icons-icon d-flex">
                <i class="icon-screen-desktop m-auto text-primary"></i>
              </div >
              <img class="imagen-servicio" src="../assets/interpretacion.png" alt="texto alternativo descriptivo" id="interpretacion" />
              <h3>Interpretacion</h3>
              <p class="lead mb-0">Servicio de interpreacion, modelamiento de cuencas y perfiles geologicos</p>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
              <div class="features-icons-icon d-flex">
                <i class="icon-layers m-auto text-primary"></i>
              </div>
              <img class="imagen-servicio" src="../assets/procesamiento.jpg" alt="texto alternativo descriptivo" id="procesamiento" />
              <h3>Procesamiento</h3>
              <p class="lead mb-0">Tenemos todo el conocimiento  tecnologia para ofrecer Migracion PSTM-PSDM, inteprolacion, vti y hti </p>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="features-icons-item mx-auto mb-0 mb-lg-3">
              <div class="features-icons-icon d-flex">
                <i class="icon-check m-auto text-primary"></i>
              </div>
              <img class="imagen-servicio" src="../assets/perforacion.jpg" alt="texto alternativo descriptivo" id="adquisicion" />
              <h3>Adquisicion</h3>
              <p class="lead mb-0">Diseño y Aquisicion de informacion sismica. Resolucion adecuada  en la geologia colombiana  </p>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
        name:'ServicesSection'        
}
</script>

<style scoped>  

.servicios{
  width: 1080px;

}

.labelServicios{
    background-color: rgb(115,115,115);  
    height: 30.98px;
    width: 1080px;
}

.tituloServicios{
    font-size: 19.37;
    font-family: tahoma sans-serif bold;
    text-align: center;
    margin-top: 14.9px;
}

.imagen-servicio{
   margin:10px;
   padding: 20px;
   width: auto;
   height: 180px;
   max-width: 300px;    
   max-height: 180px;
}

.contenedor-imagen img{
  -moz-transition: all 0.3s;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;

}
.contenedor-imagen img:hover{
  -moz-transform: scale(1.1);
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
}

</style>

