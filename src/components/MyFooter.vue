 <!--creo il componente Footer-->
 
 <template>
  <footer>
    <div class="FooterTop">
      <FooterLinks   :titolo="'DC COMICS'" />
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
    FooterLinks,
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
    };
  },
};
</script>
 
 <style lang="scss">
  footer{
    border: solid 2px blue;
  }
  .FooterBottom{
    height: 80px;
    width: 100%;
    border : solid 2px black;
  }
  .FooterTop{
   background-image: url("@/assets/img/footer-bg.jpg");
  }

</style>