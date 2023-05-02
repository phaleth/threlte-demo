<script>
	import { Canvas } from '@threlte/core';
	import Scene from '../components/Scene.svelte';
</script>

<div class="container">
	<Canvas>
		<Scene />
	</Canvas>
</div>

<style>
	.container {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
</style>
