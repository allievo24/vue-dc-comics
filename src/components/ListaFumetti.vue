<template>
     <section class="cont">
       <div class="fumetti" v-for="(fumetto ,index) in Fumetti" :key="index">
            <img :src="fumetto.thumb" alt="">
            <h4>{{fumetto.series}}</h4>
       </div>
     </section>
</template>

<script>
export default {
    nome:"ListaFumetti",
    props:{
       Fumetti:Array
    }


}
</script>

<style lang="scss">
 .cont{
    display: flex;
    flex-wrap: wrap;
    background: black;
    img{
      width:100%;
      margin:auto;
     
       

    }
    .fumetti{
        width:calc(100% / 6 - 1rem);
        margin: 2rem auto;
        padding: 2rem , 2rem;
        
       

    }
    
   
    
    
    
    
   
 }
    

</style>