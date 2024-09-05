<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<script>
	export let data;
</script>

<h1>{data.person.name}</h1>
<p>{data.person.description}</p>