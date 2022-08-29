
<!--creo il componente Main-->
<template>
    <section class="main">
       
   
        <img src="@/assets/img/buy-comics-digital-comics.png" alt=""/>
        <img src="@/assets/img/buy-comics-merchandise.png" alt=""/>
        <img src="@/assets/img/buy-comics-subscriptions.png" alt=""/>
        <img src="@/assets/img/buy-comics-shop-locator.png" alt=""/>
        <img src="@/assets/img/buy-dc-power-visa.svg" alt=""/>



    </section>
    
  
</template>

<script>

export default {
    name:'MyMain'

}
</script>

<style  lang="scss">
    .main{
        height: 80px;
        width: 100%;
        border: solid 2px red;
        display: flex;
       
        background:#0282F9 ;
    img{
        width: 100%;
        object-fit: contain;        
    }
  
   } 
     
     
   
</style>