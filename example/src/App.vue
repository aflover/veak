<template>
	<flex-window>
		<div class="center">
			<btn>Hello Veak</btn>
		</div>
	</flex-window>
</template>

<script>
	import 'veak/dist/css/veak.css'

	// public
	import Veak from 'veak'
	// import Vue from 'vue'
	// Vue.use(Veak) 
	
	export default {
		components: Veak // or private
		// components: require('veak').default // or private
	}
</script>

<style type="text/css">
	.center {
		margin: 0 auto;
		justify-content: center;
		display: flex;
		flex-direction: column;
	}
</style>