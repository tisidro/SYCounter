<script>
	import Counter from "./Counter.svelte";
</script>

<main>
	<h1>Hello SY!</h1>
	<p><Counter type="primary" /></p>
</main>

<style>
	main {
		background-color: rgb(243, 241, 241);
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	h1 {
		background-color: #76b2e4;
		text-transform: uppercase;
		font-size: 6em;
		font-weight: bold;
		font-family: "Montserrat", sans-serif;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
