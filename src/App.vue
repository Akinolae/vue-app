<template>
<Signin />
  <Button />
</template>

<script>
import Button from "./components/reuseables/Button.vue"
import Signin from "./components/Signin.vue"

export default {
  name: 'App',
  components: {
    Button,
    Signin
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
