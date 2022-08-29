 <!--creo il componente Footer-->
 
 <template>
  <footer>
    <div class="FooterTop">
      <div class="links">
        <FooterLinks :titolo="'DC COMICS'" :links="comicslinks" />
        <FooterLinks :titolo="'DC'" :links="DcLinks" />
        <FooterLinks :titolo="'SITES'" :links="siteslinks" />
        <FooterLinks :titolo="'SHOP'" :links="shoplinks" />
      </div>
      <img src="@/assets/img/dc-logo-bg.png" alt="" />
      <div class="img"></div>
    </div>

    <div class="FooterBottom">
      <div class="botton">
        <a href="#">SIGN-UP NOW!</a>
      </div>
      <div class="soscial">
        <h4>FOLLOW US</h4>
        <img src="@/assets/img/footer-facebook.png" alt="" />
        <img src="@/assets/img/footer-twitter.png" alt="" />
        <img src="@/assets/img/footer-youtube.png" alt="" />
        <img src="@/assets/img/footer-pinterest.png" alt="" />
        <img src="@/assets/img/footer-periscope.png" alt="" />
      </div>
    </div>
  </footer>
</template>
 



 <script>
import FooterLinks from "./FooterLinks";
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
      DcLinks: [
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
      ],
      siteslinks: [
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
      ],
      shoplinks: [
        {
          text: "Termes of User",
          url: "#",
        },
        {
          text: "Termes of User",
          url: "#",
        },
      ],
    };
  },
};
</script>
 










 <style lang="scss">
footer {
 

  a {
    text-decoration: none;
  }

  h4 {
    padding: 10px;
  }

  .links {
    width: 45%;
    display: flex;
    flex-wrap: wrap;
  }
}
.FooterBottom {
  padding: 2rem;
  background-color: #303030;
  border: solid 4px rgb(179, 13, 13);
  display: flex;
  justify-content: space-between;
  align-items: center;
  a {
    border: solid 2px #0282f9;
    padding: 0.5rem;
  }
  .soscial {
    display: flex;
    img {
      padding: 0rem 1rem;
    }
    h4 {
      color: #0282f9;
    }
  }
}
.FooterTop {
  display: flex;
  border: solid 2px rgb(68, 255, 0);
  background-image: url("@/assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
 
  //object-position: 50% 50%;
  //object-fit:contain ;
 

  img {
    width: 40%;
    margin-left: 6rem;
  }
}
</style>