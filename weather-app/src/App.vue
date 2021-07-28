<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld :apiKey="api"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data(){
    return{
      api: "1380719347e60d9475d99888fcab84d4",
    }
  }
}
</script>

<style>

</style>
