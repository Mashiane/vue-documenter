<template>
  <div id="app">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <vue-documenter>
      <hello-world msg="Welcome to Your Vue.js App"></hello-world>
      <vue-documenter></vue-documenter>
    </vue-documenter>
  </div>
</template>

<script>
import VueDocumenter from 'vue-documenter'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    VueDocumenter,
    HelloWorld,
  }
}
</script>

<style lang="scss">

</style>
