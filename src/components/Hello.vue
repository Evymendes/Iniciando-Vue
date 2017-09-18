<template>
  <div class="hello">
    <h1>Vai na Web</h1>
    <h2>Modulo 2</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Aula 1</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Aula 2</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank">Aula 3</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Aula 4</a></li>
    </ul>
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
