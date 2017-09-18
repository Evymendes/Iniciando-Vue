<template>
<div >
	<h1>Vai na Web</h1>
  <h2>Modulo 2</h2>
  <Gato> </Gato>
<router-link to="Aula1">Aula 1</router-link>
<router-link to="Aula2">Aula 2</router-link>
<router-link to="Aula3">Aula 3</router-link>

</div>	
</template>

<script>
import Gato from './Gato'

export default {
  name: 'Ola',
  components: {Gato},
  data () {
    return {
      nome: '',
      idade: ''
    }
  }
}
</script>

<style scoped>
</style>