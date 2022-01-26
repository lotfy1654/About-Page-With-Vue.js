<template>
  <div id="app">
    <the-desktop id="desktop-nav" />
    <the-mobile-nav id="mobile-nav" />
    <div class="view-container"></div>
    <router-view />
  </div>
</template>

<script>
import theDesktop from "@/components/theDesktop.vue";
import theMobileNav from "@/components/theMobileNav.vue";
export default {
  components: {
    theDesktop,
    theMobileNav,
  },
};
</script>

<style lang="scss" scoped>
.view-container {
  width: 79vw;
  padding: 0.5em;
  margin-left: 20vw;
  box-sizing: border-box;
  // min-height: 100vh;
}

#mobile-nav {
  display: none;
}

@media screen and (max-width: 1096px) {
  #desktop-nav {
    display: none;
  }
  #mobile-nav {
    display: flex;
  }
}
</style>
