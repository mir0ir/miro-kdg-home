<script>
	import "../app.postcss";
    import Header from './Header.svelte';
    import './styles.css';
</script>

<div class="app flex flex-col min-h-screen bg-black max-w-screen overflow-x-hidden">
	<header></header>

	<main 
		class="
			box-border
			flex flex-col flex-1 
			p-4 m-8 mb-4 
			border-4 border-dashed border-green-500
			">
		<slot></slot>
	</main>

	<footer class="text-gray-100 flex flex-col justify-center items-center p-3">
		<!-- <p>Visit <a href="https://kit.svelte.dev" class="font-bold">kit.svelte.dev</a> to learn SvelteKit</p> -->
	</footer>
</div>

<style>
	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
