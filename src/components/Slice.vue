<template>
         <div id="start" class="carousel-cnt">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                  <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                  <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                  <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img class="d-block w-100 cropped img" src="../assets/slider1.jpg" alt="First slide">
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100 cropped" src="../assets/slider2.jpg" alt="Second slide">
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100 cropped" src="../assets/slider3.jpg" alt="Third slide">
                  </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only"></span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only"></span>
                </a>
              </div>
         </div>


</template>


<script>
    export default {
            name: "Slice",        
        }
</script>

<style scoped>
.carousel-cnt{
    display: flex;
    width: 100%;
    
}

.carousel-item{
    width: 100%;
    height: 400px;
}

.carousel-item>.cropped{
    height: 100%;   
    object-fit:cover;
    object-position: 0%, 0%;    
    margin-left: auto;
}

</style>