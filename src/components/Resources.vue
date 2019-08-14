<template>
	<div class="resources">
		<h2>Resources</h2>
		<p>Money: {{money}}</p>
	</div>
</template>

<script>
	export default {
		name: 'Resources',
		props: {
			money: Number
		}
	}
</script>
