<template>
  <div class="container">
    <article-3 />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  head() {
    return {
      title: "Mobile Photography: Take your photography to the next level - Viewfinder | SUPA",
      meta: [
        { hid: 'description', name: 'description', content: 'Before the days of the smartphone, capturing a moment in real-time was not as easy as just pulling out a smartphone from your pocket. Nowadays, if you want to capture a moment in real-time, remember, the best camera is always in your pocket. But you are taking photos constantly with your smartphone and wondering why your photos don’t have that ‘WOW’ factor you see around on Instagram or somewhere else, is that all about you don’t have your own expensive camera?' },
        { hid: 'og:image', property: 'og:image', content: '/article-3.png' },
        { hid: 'og:description', property: 'og:description', content: 'Before the days of the smartphone, capturing a moment in real-time was not as easy as just pulling out a smartphone from your pocket. Nowadays, if you want to capture a moment in real-time, remember, the best camera is always in your pocket. But you are taking photos constantly with your smartphone and wondering why your photos don’t have that ‘WOW’ factor you see around on Instagram or somewhere else, is that all about you don’t have your own expensive camera?' },
        { hid: 'og:url', property: 'og:url', content: 'https://viewfinder.supasust.org/mobile-photography-take-your-photography-to-the-next-level/' },
        { hid: 'og:title', property: 'og:title', content: "Mobile Photography: Take your photography to the next level - Viewfinder | SUPA" }
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