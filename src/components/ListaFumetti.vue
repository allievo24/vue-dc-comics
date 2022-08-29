<template>
     <section class="fumetti">
       <div class="cont" v-for="(fumetto ,index) in Fumetti" :key="index">
            <img :src="fumetto.thumb" alt="">
            <h4>{{fumetto.type}}</h4>
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
 .fumetti{
    display: flex;
    flex-wrap: wrap;
    border:solid 2px blue;
    background: black;
    img{
      width:100%;
      border:solid 2px blue;
      margin:auto;
     
       

    }
    .cont{
        width:calc(100% / 6 - 1rem);
        margin: auto;
        border:solid 2px rgb(0, 255, 47);
       

    }
    
   
    
    
    
    
   
 }
    

</style>