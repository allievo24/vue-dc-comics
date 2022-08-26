<template>
  <div class="linkfooter">
    <h4>{{titolo}}</h4>
        <ul>
            <li>
                <a href="#">Characters</a>
            </li>
        </ul>
  </div>
</template>

<script>

export default {
    name: "FooterLinks",
    props:{
        titolo: String,
        links: Array,
    }

}
</script>

<style lang="scss">

</style>