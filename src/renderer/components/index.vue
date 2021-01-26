<template>
  <div id="container">
    hello1
  </div>
</template>

<script>

  export default {
    name: 'index',
    components: { },
    methods: {
      open (link) {
        this.$electron.shell.openExternal(link)
      }
    }
  }
</script>

<style>
</style>
