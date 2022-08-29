<!--creo il componente Header-->
<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="logo" />
    <nav>
      <ul>
        <li v-for="(link,index) in links" :key="index">
          <a :href="link.url">{{link.text}}</a>
        </li>
      </ul>
    </nav>
    <div class="Bottom">-->Content goes here --</div>
  </header>
</template>

<script>
export default {
  name: "MyHeader",
  
  data() {
    return {
      links: [
        {
          text: "CHARACTERS",
          url: "#",
          active: false,
        },
        {
          text: "COMICS",
          url: "#",
          active: true,
        },
        {
          text: "MOVIES",
          url: "#",
          active: false,
        },
        {
          text: "TV",
          url: "#",
          actve: false,
        },
        {
          text: "GAMES",
          url: "#",
          actve: false,
        },
        {
          text: "COLLECTIBLES",
          url: "#",
          actve: false,
        },
        {
          text: "VIDEOS",
          url: "#",
          actve: false,
        },
        {
          text: "FANS",
          url: "#",
          actve: false,
        },
        {
          text: "NEWS",
          url: "#",
          actve: false,
        },
        {
          text: "SHOP",
          url: "#",
          actve: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
    header{
         border : 2px solid black;
         display: flex;
         align-items: center;
          
            
      ul{
        
        display:flex; 
        list-style: none;
      

      li{
        padding: 1rem; 
        
        a{
          text-decoration: none;
          color:black;

        }
          
      }
      
      }
      

    }


</style>