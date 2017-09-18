<template>
	<div>
		<h1>Aula 3</h1>
		<h3>Revisão</h3>
		<Aula3gif> </Aula3gif><br>
		<router-link to="Aula1"> Aula 1 </router-link>
		<router-link to="Aula2"> Aula 2 </router-link>

	</div>
</template>

<script>
	import Aula3gif from './Aula3gif'

export default {
  name: 'Aula3',
  components: {Aula3gif},
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