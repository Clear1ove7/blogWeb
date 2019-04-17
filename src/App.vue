<template>
	<div id="app">
		<div class="app-content">
			<headers></headers>
			<router-view />
		</div>
		
	</div>
</template>

<script>
	import headers from './components/header'
	export default {
		name: 'App',
		components: {
			headers
		}
	}
</script>

<style lang="scss">
@import './assets/common';
#app{
	width: 100%;
	height: 100%;
	.app-content {
		width: 100%;
		height: 100%;
		position: relative;
		overflow: hidden;
		overflow-y: scroll;
	}
}
	
</style>
