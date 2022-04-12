<main>
	<h1 class="header">alfvar</h1>
	<h2>En lite snällare rubrik</h2>
	<h3>En snäll rubrik</h3>

	<p>Brödtext och ett exempel på några ord på rad i en mening. Stilligt!</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background-color: none;
	}

	.header {
		font-size: 8em;
		margin: 0.01em;
		padding: 0em;
		border-style: dashed;
		display: flex;
		justify-content: center;
	}

	h2 {
		border-style: dashed;
	}

	h3 {
		border-style: dashed;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
