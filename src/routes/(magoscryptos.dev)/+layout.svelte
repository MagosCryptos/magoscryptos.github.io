<script>
	import '../../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?&family=Fira+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Cinzel+Decorative:wght@400;700;900&family=Cinzel:wght@400..900&family=Saira:ital,wght@0,100..900;1,100..900&display=swap"
		rel="stylesheet"
	/>

	<title>Magos Cryptos</title>

	<meta name="theme-color" content="#16161D" />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
</svelte:head>

<!-- naked layout -->
{@render children()}
