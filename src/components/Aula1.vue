<template>
  <div class="hello">
    <h1>Aula 1</h1>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Aula 1</a></li>
      <li><router-link to="Aula2">Aula 2</router-link></li>
      <li><router-link to="Aula3">Aula 3</router-link></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Aula 4</a></li>
    </ul>
    <router-link to="/">Inicio</router-link>
  </div>
</template>

<script>
export default {
  name: 'Ola',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
  color: blue;
}
</style>
