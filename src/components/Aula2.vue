<template>
<div >
	<h1>Aula 2</h1>
	<label>Nome:</label>
	<input v-model="nome"><br>
	<label>Idade:</label>
	<input v-model="idade"><br>
  <label>E-mail:</label>
  <input v-model="email"><br>
  <label>Telefone:</label>
  <input v-model="telefone"><br>
  <label>Endereço:</label>
  <input v-model="endereco"><br>

<router-link to="/">Inicio</router-link>
<router-link to="Aula1"> Aula 1 </router-link>
<router-link to="Aula3"> Aula 3 </router-link>

  <p>{{nome}}</p>
  <p>{{idade}}</p>
  <p>{{email}}</p>
  <p>{{telefone}}</p>
  <p>{{endereco}}</p>
</div>	
</template>

<script>
export default {
  name: 'Aula2',
  data () {
    return {
      nome: '',
      idade: '',
      email: '',
      telefone: '',
      endereco: ''
    }
  }
}
</script>

<style scoped>
input {
  margin:  1%;
}
</style>