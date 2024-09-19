<script>
	export let data;
	import { draw } from 'svelte/transition';
</script>

<main>
	<article>
		<img src="/images/background-image.jpg" alt="background"/>
		<h1>{data.person.name} {data.person.surname}</h1>
	</article>
</main>

<style>
	main {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}

	article {
		position: relative;
		width: 20em;
		height: auto;
		/* text-align: center; */
		background-color: black;
	}

	img {
		width: 100%;
		height: auto;
		/* border: 2em solid black; */
	}

	h1 {
		/* text-align: center; */
		position: absolute;
		top: 20%;
		left: 50%;
		transform: translate(-50%, -50%);
		color: white;
		font-family: 'Fascinate Inline';
		font-size: 2em;
		text-align: center;
	}

</style>