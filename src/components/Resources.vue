<template>
	<div class="resources">
		<h2>Resources</h2>
		<p>Money: {{money}}</p>
	</div>
</template>

<script>
	import { setInterval } from 'timers'

	export default {
		name: 'Resources',
		props: {
			money: Number
		},
		created: function() {
			setInterval(function () {
				this.money += 1
			}, 1000)
		}
	}
</script>
