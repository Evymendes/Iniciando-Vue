<template>
	<div>
		<h1>Campeonato Brasileiro</h1>
		<h2>Flamengo vc Corinthians</h2>
		<img src="http://www.flamengo-futebol.com/imagens/flamengo.jpg">
		<img src="https://www.google.com.br/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=0ahUKEwiqtefDra_WAhXDkZAKHdOwC8gQjRwIBw&url=https%3A%2F%2Fwww.meutimao.com.br%2Fforum-do-corinthians%2Fbate-papo-da-torcida%2F165292%2Fmascote_e_gaviao_ou_mosqueteiro&psig=AFQjCNFTs3sOL3r6Ps03Ru0O7A9q7gBXiA&ust=1505845406044238">
		<button v-on:click="golclique()">+</button>
		<button v-on:click="anulaclique">-</button>
		<button v-on:click="novojogo">Novo Jogo</button>
		<p>Gol: {{clique}}</p>
	</div>
		
</template>

<script>
	export default {
  name: 'Campeonato Brasileiro',
  data () {
    return {
      titulo: 'Futebol',
      clique: 0
    }
  },
	methods: {
		golclique(){
			return this.clique++
		},
		anulaclique(){
			return this.clique--
		},
		novojogoclique(){
			return this.clique = 0
		}
	}
}
</script>

<style>
	
</style>