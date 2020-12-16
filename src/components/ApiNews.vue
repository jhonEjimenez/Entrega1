<template>
              
        <div id="news" class="news-sect container-fluid">
            <div class="new-cnt" v-for="(n, index) of news" :key="index">
                <div class="img-new-cnt">
                    <img class="cropped" :src="n.urlToImage" alt="">
                </div>
                <div class="text-new-cnt">
                    <h4>{{n.title}}</h4>
                    <p>
                        {{n.description}}
                    </p>                                      
                </div>
                <a class="link-info" :href="n.url" target="_blank">Ver mas</a>  
            </div>          
        </div>  
</template>

<script>

export default {
  name: 'NewsSection',
  props: {
    msg: String
  },
  data(){
    return{
      news : null      
    }
  },
  created(){

    var url = 'https://newsapi.org/v2/everything?q=petroleum&apiKey=f67d836806de4a75a55adc54fd41c1fc'
    var req = new Request(url);
    fetch(req)
        .then(function(response) {
            return response.json()
        }).then(n =>{
            this.news = n.articles.slice(0,4)                      
        })
}
  
} 

</script>

<style scoped>



  .news-sect{    
    width: 100%;
    display:flex;
    align-items: left;
    flex-wrap: wrap;
    font-family: Tahoma, sans-serif;
   
}

.new-cnt{
    background-color: rgba(25,153, 159,0.5);
    display:flex;
    width:calc(50% - 10px);    
    padding: 15px;
    justify-content: space-around;
    border: 3px rgb(25,153, 159) solid;
    position:relative;
    margin: 5px;    
}

.new-cnt:hover{
    background-color: rgba(25,153, 159,1);
}

.img-new-cnt>.cropped{
     
    width:250px;
    height: 250px;
    object-fit:cover;
    object-position: 10%, 10%;
    border-radius: 10px;
    margin-left: auto;
    margin-right: auto;

}

.text-new-cnt{
    background-color: rgb(255,255,255);
    border-radius: 10px;
    margin-left: 20px;

}

.text-new-cnt>p{
    padding: 10px;
    text-align: justify;

}

.text-new-cnt>h4{
    padding: 10px;
    text-align: justify;

}

.link-info{
    color: rgb(0,0,0);
    background-color: rgb(115,115,115);
    color: rgb(255,255,255);
    text-decoration:none;
    padding:10px;   
    border-radius: 5px;
    position: absolute;
    bottom:10px;
    right: 10px;
   
   
   

}

.link-info:hover{
    border: rgb(115,115,115) 5px solid;
    background-color: rgb(255,255,255);
    color: rgb(0,0,0);
}

</style>