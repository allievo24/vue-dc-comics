 <!--creo il componente Footer-->
 
 <template>
  <footer>
    <div class="FooterTop">
      <FooterLinks   :titolo="'DC CoMICS'" :links="comicslinks"/>
      <FooterLinks   :titolo="'DC'" :links="DcLinks" />


    </div>
    <div class="FooterBottom">
        <h1>MyFooter</h1>
    </div>
    
  </footer>
</template>
 



 <script>
import FooterLinks from './FooterLinks';
export default {
  name: "MyFooter",
  components: {
    FooterLinks
  },
   data() {
    return {
      comicslinks: [
        {
          text: "CHARACTERS",
          url: "#",
        },
        {
          text: "COMICS",
          url: "#",
        },
        {
          text: "MOVIES",
          url: "#",
        },
        {
          text: "TV",
          url: "#",
        },
        {
          text: "GAMES",
          url: "#",
        },
        {
          text: "COLLECTIBLES",
          url: "#",
        },
        {
          text: "VIDEOS",
          url: "#",
        },
        {
          text: "FANS",
          url: "#",
        },
        {
          text: "NEWS",
          url: "#",
        },
      ],
 DcLinks: [
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },
            {
               text :"Termes of User",
                url: "#",
            },

        ]




    };
  },
}
</script>
 










 <style lang="scss">
  
  footer{
    display: flex;
    flex-wrap: wrap;
    border: solid 2px blue;
    background-image: url("@/assets/img/footer-bg.jpg");
    a {
      text-decoration: none;
    }
    h4{
      padding: 10px;
    }
  }
  .FooterBottom{
    height: 80px;
    
    border : solid 2px rgb(179, 13, 13);
  }
</style>