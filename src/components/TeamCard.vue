<template>
    <div>
        <div class="card text-white  cajas card h-100 ">
            <div class="d-flex justify-content-center p-2 ">
                <img :src="member.image" alt="Foto Perfil"> 
            </div>
            <div class="card-body">
                <h5 class="card-title">{{member.nombre}}</h5>
                <p class="card-text"> {{member.descripcion}}</p>
            </div>
            <div class="card-footer">
                <small class="text-muted">Last updated 3 mins ago</small>
            </div>
        </div>               
    </div>

</template>
<script>
    export default {
        name: "TeamCard",
        props: ['member']
        
    }
</script>

<style scoped>

.cajas{    
    background-color: rgb(140,204,207);
    border: 20px white solid;
    margin-bottom :20px;
   
}

.cajas img{
    width:  200px;
    height: 200px ;
    background: rgb(25,153,159);
    border: 10
}
.cajas:hover{
    background-color: rgb(25,153, 159);
}


</style>
