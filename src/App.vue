<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png" />
		<HelloWorld msg="Welcome" />
		<Resources money="100" />
	</div>
</template>
<script>
	import HelloWorld from './components/HelloWorld.vue'
	import Resources from './components/Resources.vue'

	export default {
		name: 'app',
		components: {
			HelloWorld,
			Resources
		}
	}
</script>
<style>
	#app {
		color: #2c3e50;
		font-family: "Avenir", Helvetica, Arial, sans-serif;
		margin-top: 60px;
		text-align: center;
		-moz-osx-font-smoothing: grayscale;
		-webkit-font-smoothing: antialiased;
	}
</style>
