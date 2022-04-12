<main>
	<h1 class="logo">alfvar</h1>
	<p class="subheader">is studying interaction design in Halmstad</p>
	<div class="divider" />
	<div class="topnav">
		<a class="active" href="#home">UX</a>
		<a href="#news">Artwork</a>
		<a href="#contact">Music</a>
		<a href="#about">About</a>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	.logo {
		font-size: 8em;
		margin-top: -0.4em;
		margin-bottom: -0.2em;
		display: flex;
		justify-content: center;
		padding: 0;
	}

	.subheader {
		font-size: 1.2em;
		margin: 0;
	}

	.divider {
		width: 100%;
		height: 2px;
		background-color: #000;
		margin: 0.75em 0;
	}

	.topnav a {
		display: inline-block;
		padding: 1px 16px;
		font-size: 1.2em;
		font-weight: 700;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
