<template lang="pug">
  header.mb-8
    h1.text-4xl.font-hairline Big Smelly Robot
    h2.text-3xl {{ title }}
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: ''
    }
  }
}
</script>
