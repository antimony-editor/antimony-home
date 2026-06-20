<script>
	import favicon from '/logo.svg';
	import '$lib/assets/style.css';

	let { children } = $props();

	export const prerender = true;
</script>

<svelte:head>
	<title>Antimony - Home</title> 
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
