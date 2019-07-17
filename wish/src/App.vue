<template>
	<div id="app">
		<wish-task0 />
	</div>
</template>

<script>
	import WishTask0 from './views/Task0.vue'
	//left='100px' top='200px' width='100px' height='200px' value='第一条' :items="['第一条', '第二条']"
	export default {
		name: 'app',
		components: {
			WishTask0
		}
	}
</script>

<style>
	* {
		margin: 0px;
		padding: 0px;
	}

	#app {
		font-family: '微软雅黑', Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
</style>
