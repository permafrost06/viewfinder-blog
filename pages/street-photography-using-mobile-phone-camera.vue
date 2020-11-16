<template>
  <div class="container">
    <article-2 />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  head() {
    return {
      title: "Street Photography using Mobile Phone Camera - Viewfinder | SUPA",
      meta: [
        { hid: 'description', name: 'description', content: 'Photography is an art of vision that can be expressed through a bunch of pixels and hence should not always depend on high budget devices. Nowadays Smartphone has replaced cameras and other devices in many aspects of photography. It is because budget phones have decent cameras and can get you some amazing results. Though the camera and lens in your Smartphone isn’t as good as a professional digital camera, but in street photography, using a phone sometimes can be of advantage.' },
        { hid: 'og:image', property: 'og:image', content: '/article-2.jpg' },
        { hid: 'og:description', property: 'og:description', content: 'Photography is an art of vision that can be expressed through a bunch of pixels and hence should not always depend on high budget devices. Nowadays Smartphone has replaced cameras and other devices in many aspects of photography. It is because budget phones have decent cameras and can get you some amazing results. Though the camera and lens in your Smartphone isn’t as good as a professional digital camera, but in street photography, using a phone sometimes can be of advantage.' },
        { hid: 'og:url', property: 'og:url', content: 'https://viewfinder.supasust.org/street-photography-using-mobile-phone-camera/' },
        { hid: 'og:title', property: 'og:title', content: "Street Photography using Mobile Phone Camera - Viewfinder | SUPA" }
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