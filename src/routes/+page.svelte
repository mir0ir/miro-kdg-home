<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
	import KdgSvg from '../lib/components/Media/KdgSvg.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Miro Polfliet KdG" />
</svelte:head>

<section 
	class='
		text-green-500 w-full h-full
		flex items-center flex-col justify-center'>
	<h1>
		Welcome to my Website <br/>
		(Work in Progress)
	</h1>

	<h2>
		by <strong>Miro Storm Polfliet</strong>
	</h2>

	<KdgSvg/>
</section>