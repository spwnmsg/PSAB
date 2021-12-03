<template>
  <MessageArea id="message-area" class="left-align"></MessageArea>
</template>

<script>
import MessageArea from './components/MessageArea.vue'

export default {
  name: 'App',
  components: {
    MessageArea
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
