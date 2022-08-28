<template>
  <div class="linkfooter">
    <h4>{{ titolo }}</h4>
    <ul>
      <li v-for="(link, index) in links" :key="index">
        <a :href="link.url">{{ link.text }}</a>
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
.linkfooter {
  a {
    text-decoration: none;
  }
}
</style>