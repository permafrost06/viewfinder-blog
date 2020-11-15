<template>
  <div class="nav">
    <nuxt-link to="/" class="logo" aria-label="homepage"
      ><span class="supa-font">SUPA</span> | Viewfinder</nuxt-link
    >
  </div>
</template>

<script>
export default {
  name: 'navBar',
}
</script>

<style lang="scss" scoped>
.logo {
  font-size: 3em;
  margin: 0 auto;

  @media (max-width: 1000px) {
    font-size: 2em;
  }

  @media (max-width: 550px) {
      font-size: 1.5em;
  }
}

.nav {
  --text: #f4f4f4;
  --text-inverse: #333;
  --background: rgba(0, 0, 0, 1);

  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 999;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1em;
  transition: background 250ms ease-in;
  background: var(--background);
  color: var(--text);

  @media (max-width: 800px) {
    display: block;
    text-align: center;
  }
}
</style>