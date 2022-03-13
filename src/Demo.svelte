<script lang="ts">
	export let name: string;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style type="scss">
	@import './global';

	h1 {
		color: #000;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
</style>