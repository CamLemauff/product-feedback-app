<template>
  <div id="app">
    <suggestions></suggestions>
  </div>
</template>

<script>
import Suggestions from './components/Suggestions.vue'

export default {
  name: 'app',
  components: {
    Suggestions
  }
}
</script>

<style lang="scss">
#app {
  color: #3A4374;
  padding-top: 60px;
  background-color: #F7F8FD;
  display: flex;
  justify-content: center;
  height: 100%;
}
</style>
