 <!--creo il componente Footer-->
 
 <template>
  <footer>
    <div class="FooterTop">
      <FooterLinks   :titolo="'DC CoMICS'" :links="comicslinks"/>
      <FooterLinks   :titolo="'DC'" :links="DcLinks" />
:DcLinks="DcLinks"

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
}
</script>
 
 <style lang="scss">
  footer{
    border: solid 2px blue;
    background-image: url("@/assets/img/footer-bg.jpg");

  }
  .FooterBottom{
    height: 80px;
    width: 100%;
    border : solid 2px black;
  }
</style>