<script>

// import AppHeader from './components/AppHeader.vue'

import AppMain from './components/AppMain.vue'

// import AppBannerIcons from './components/AppBannerIcons.vue';

// import AppFooter from './components/AppFooter.vue'

export default {
  data() {
    return {

    }
  },
  components: {
    // AppHeader,
    AppMain,
    // AppBannerIcons,
    // AppFooter
  }
}

</script>

<template>

  <!-- <AppHeader /> -->
  <AppMain />
  <!-- <AppBannerIcons /> -->
  <!-- <AppFooter /> -->

</template>

<style lang="scss">
@use './styles/main.scss' as *;
</style>
