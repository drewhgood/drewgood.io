<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld msg="Welcome, Homie!"/>
    <h1> Nice To have You. </h1>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '../components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
