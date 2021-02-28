<script lang="ts">
	import Nav from '../components/Nav.svelte';

	export let segment: string;
</script>

<style global lang="postcss">
	/* purgecss start ignore */
	@tailwind base;
	@tailwind components;
	/* purgecss end ignore */
	@tailwind utilities;
</style>


<Nav {segment}/>

<main>
	<slot></slot>
</main>
