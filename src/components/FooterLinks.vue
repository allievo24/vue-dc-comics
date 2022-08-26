<template>
  <div class="linkfooter">
    <h4>{{titolo}}</h4>
        <ul>
            <li v-for="(link , index) in comicslinks " :key="index" >
                <a :href="link.url">{{link.text}}</a>
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