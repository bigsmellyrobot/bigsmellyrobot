<template lang="pug">
.main-body.font-sans.min-h-screen.pb-8
  site-header
  nuxt
</template>

<script>
import SiteHeader from '~/components/Header.vue'

export default {
  components: {
    SiteHeader
  }
}
</script>

<style lang="scss">
@import 'assets/css/settings.scss';
body {
  max-width: 100vw;
  overflow-x: hidden;
  background: $white2;
}
.main-body {
  &, a {
    color: $gray;
  }

  .gray-95 {
    background: $white-95;
  }

  .nav-btn {
    border-color: $gray;
  }
}
.text-justify p:not(:first-child) {
  text-indent: 2rem
}
a {
  transition: color .25s, border-width .25s
}
</style>
