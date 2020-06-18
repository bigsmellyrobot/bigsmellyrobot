<template lang="pug">
  main.p-2.pt-16.max-w-sm
    page-header(title='About')
    section.text-justify.leading-normal
      p.font-hairline(
        v-for='p in about'
        ) {{ p }}
</template>

<script>
import PageHeader from '~/components/PageHeader.vue'

export default {
  components: {
    PageHeader
  },
  head() {
    return {
      title: 'Big Smelly Robot'
    }
  },
  data: function() {
    return {
      about: [
        'I’m not really sure what this is about yet.'
      ]
    }
  }
}
</script>

<style lang="sass">
  .this-shouldnt-exist
    display: none
</style>
