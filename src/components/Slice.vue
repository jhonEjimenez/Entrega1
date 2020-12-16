<template>
         <!-- carousel -->
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
nav{
    width:100%;
    display:flex;
    height: 64px;
    background-color: rgb(25,153, 159);
    
}

.img-container{   
    margin-left: 15.35px;
    padding-top: 6.2px;
    padding-bottom: 6.2px;
}

.img-container>img{
    width: 123px;
}



.options-cnt{
    width: calc(100% - 123px);
}


.options-cnt>ul{
    font-family: Tahoma, sans-serif;
    font-size: 19.17px;    
    display:flex;
    justify-content: flex-end;
    list-style-type: none;
    padding-top: 18.15px;
    padding-bottom: 18.15px;
    margin-bottom: 0px;
}

.options-cnt>ul>li{
    margin-left:20.61px;
    margin-right: 20.61px;
    align-items: right;
}

.options-cnt>ul>li>a, .options-cnt>ul>li>a:hover {
    color: rgb(255,255,255);
    text-decoration:none;
    
}

</style>