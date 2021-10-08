<template>
  <form>
    <label >email</label><br/>
    <input type="text" v-model="email" id="email" placeholder="email" required /><br/>
    <label>password</label>
    <input type="password" id="password" placeholder="password" required />
  </form>
</template>

<script>
import {signin} from "../services/auth/signin"

export default {
  name: 'Signin',
  props: {
    msg: String
  },
  
  methods: {
      signin
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.form {

}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
