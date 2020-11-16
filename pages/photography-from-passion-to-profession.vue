<template>
  <div class="container">
    <article-1 />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  head() {
    return {
      title: "Photography: From Passion to Profession - Viewfinder | SUPA",
      meta: [
        { hid: 'description', name: 'description', content: 'Human by nature, are passion driven. Think of a new born, in their toddler years, whatever they do, everyone cheers them up, every single move is welcomed with immense joy, every small step forward is recorded. As time passes by, priorities change, we are chasing that inevitable dream of maintaining social standards but where does passion lie by? Most of us, are lost in the race of life, we bury our passion and led by a life set up by the societal standards.' },
        { hid: 'og:description', property: 'og:description', content: 'Human by nature, are passion driven. Think of a new born, in their toddler years, whatever they do, everyone cheers them up, every single move is welcomed with immense joy, every small step forward is recorded. As time passes by, priorities change, we are chasing that inevitable dream of maintaining social standards but where does passion lie by? Most of us, are lost in the race of life, we bury our passion and led by a life set up by the societal standards.' },
        { hid: 'og:url', property: 'og:url', content: 'https://viewfinder.supasust.org/photography-from-passion-to-profession/' },
        { hid: 'og:title', property: 'og:title', content: "Photography: From Passion to Profession - Viewfinder | SUPA" }
      ]
    }
  }
})
</script>

<style lang="scss" scoped>
.container {
  margin-top: 20vh;
}
</style>