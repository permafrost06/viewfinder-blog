<template>
  <div>
    <navBar />
    <div class="container">
      <Nuxt />
    </div>
    <footerBar />
  </div>
</template>

<script lang="ts">
import navBar from '../components/navBar.vue'
import footerBar from '../components/footerBar.vue'

import Vue from 'vue'
export default Vue.extend({
  components: { navBar,footerBar }
})
</script>

<style lang="scss">
@font-face {
  font-family: 'bauhaus_93regular';
  src: url('~assets/fonts/bauhs93-webfont.woff') format('woff'),
    url('~assets/fonts/bauhs93-webfont.woff2') format('woff2');
}

@font-face {
  font-family: 'Kalpurush';
  src: url('~assets/fonts/Kalpurush.eot');
  src: url('~assets/fonts/Kalpurush.woff') format('woff'),
       url('~assets/fonts/Kalpurush.ttf') format('truetype'),
       url('~assets/fonts/Kalpurush.svg#Kalpurush') format('svg'),
       url('~assets/fonts/Kalpurush.eot?#iefix') format('embedded-opentype');
  font-weight: normal;
  font-style: normal;
}

html {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  color: white;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  background-color: #202020;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

a {
  color: white;
  text-decoration: none;

  :hover {
    text-decoration: underline;
  }
}

h4 {
  font-weight: 300;
}

p {
  margin: 1em 0;
}

.supa-font {
  font-family: 'bauhaus_93regular', serif;
}

.bangla {
  font-family: 'Kalpurush', serif;
}

.regular-font {
  font-family: 'Montserrat', sans-serif;
  font-size: 1rem;
}

.bangla-size-fix {
  font-size: 19px;
  line-height: 23px;
}

.bold {
  font-weight: 700;
}

.italic {
  font-style: italic;
}

.container {
  margin-left: auto;
  margin-right: auto;
  padding: 0 0.5em;
  width: 100%;
  
  @media (min-width: 500px) {
    max-width: 500px;
    padding: 0 1em;
  }
  
  @media (min-width: 700px) {
    max-width: 700px;
  }

  @media (min-width: 900px) {
    max-width: 900px;
  }
}

.no-padding {
  padding: 0;
}
</style>
