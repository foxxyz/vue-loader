<style lang="stylus">
font-stack = Helvetica, sans-serif
primary-color = #999
body
  font 100% font-stack
  color primary-color
</style>

<template lang="pug">
div
  h1 This is the app
  comp-a
  comp-b
</template>

<script>
export default {
  data () {
    return { msg: 'Hello from Babel' }
  }
}
</script>
