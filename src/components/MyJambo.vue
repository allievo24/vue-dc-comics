<template>
   <div class="jambo">
            <img src="@/assets/img/jumbotron.jpg" alt="">
        </div>
</template>

<script>
export default {
    nome:"MyJambo",

}
</script>



<style lang="scss">
.jambo{
    height: 300px;

    img{
        width: 100%;
        height: 100%;
        //background-repeat: no-repeat;
        //background-size: cover;
 
       object-fit:fill;
       object-position:50% 50%;
    }
   
    
 }

</style>