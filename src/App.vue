<!--Uso i componenti creati richiamandoli nel div id="app"-->
<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MyFooter/>
  </div>
</template>

<script>
//importo i componenti creati
import MyHeader from './components/MyHeader.vue'
import MyMain   from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'


//registro i componenti
export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
  }
}
</script>

<style lang="scss">
#app {
  /*font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;*/
  
}
  @import "./styles/general.scss"
</style>
