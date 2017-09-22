<template>
  <div id="app">
    <hello greeting="Hello"></hello>
  </div>
</template>

<script>
import Hello from './components/Hello.vue';

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style lang="scss">
@import "./scss/variables.scss";
@import "./scss/global.scss";
</style>