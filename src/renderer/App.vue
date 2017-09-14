<template>
  <div id="main">
    <h1>Main View</h1>
    <jester />
  </div>
</template>

<script>
  import Jester from './jester.vue'

  export default {
    name: 'app',
    components: { jester: Jester },
    data () {
      return {
      }
    }
}
</script>
