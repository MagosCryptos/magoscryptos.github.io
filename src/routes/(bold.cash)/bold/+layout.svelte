<script>
	import '../../../app.css';
	import { base } from '$app/paths';

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

<nav class="w-dvw">
	<ul>
		<li>
			<a href="{base}/bold">Dashboard</a>
		</li>

		<li>
			<a href="{base}/bold/borrow">Borrow</a>
		</li>

		<li>
			<a href="{base}/bold/earn">Earn</a>
		</li>

		<li>
			<a href="{base}/bold/leverage">Leverage</a>
		</li>

		<li>
			<a href="{base}/bold/loan">Loan</a>
		</li>

		<li>
			<a href="{base}/bold/redeem">Redeem</a>
		</li>

		<li>
			<a href="{base}/bold/stake">Stake</a>
		</li>
	</ul>
</nav>

<div class="h-dvh w-dvw bg-slate-900">
	<div class="navbar bg-slate-800">
		<div
			class="font-cinzel-decorative flex hidden h-full items-center bg-slate-700 text-[2rem] font-bold"
		>
			BOLD
		</div>

		<div class="mx-auto flex h-full max-w-[40rem] bg-slate-800">
			<div class="navbar-item bg-slate-700">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 24 24"
					fill="currentColor"
					class="size-8"
				>
					<path
						fill-rule="evenodd"
						d="M3 6a3 3 0 0 1 3-3h2.25a3 3 0 0 1 3 3v2.25a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6Zm9.75 0a3 3 0 0 1 3-3H18a3 3 0 0 1 3 3v2.25a3 3 0 0 1-3 3h-2.25a3 3 0 0 1-3-3V6ZM3 15.75a3 3 0 0 1 3-3h2.25a3 3 0 0 1 3 3V18a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-2.25Zm9.75 0a3 3 0 0 1 3-3H18a3 3 0 0 1 3 3V18a3 3 0 0 1-3 3h-2.25a3 3 0 0 1-3-3v-2.25Z"
						clip-rule="evenodd"
					/>
				</svg>
				<!-- Dashboard -->
			</div>
			<div class="navbar-item bg-slate-700">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="size-8"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m3.75 9v7.5m2.25-6.466a9.016 9.016 0 0 0-3.461-.203c-.536.072-.974.478-1.021 1.017a4.559 4.559 0 0 0-.018.402c0 .464.336.844.775.994l2.95 1.012c.44.15.775.53.775.994 0 .136-.006.27-.018.402-.047.539-.485.945-1.021 1.017a9.077 9.077 0 0 1-3.461-.203M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z"
					/>
				</svg>

				<!-- Borrow -->
			</div>
			<div class="navbar-item bg-slate-700">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 24 24"
					fill="currentColor"
					class="size-8"
				>
					<path
						fill-rule="evenodd"
						d="M11.47 10.72a.75.75 0 0 1 1.06 0l7.5 7.5a.75.75 0 1 1-1.06 1.06L12 12.31l-6.97 6.97a.75.75 0 0 1-1.06-1.06l7.5-7.5Z"
						clip-rule="evenodd"
					/>
					<path
						fill-rule="evenodd"
						d="M11.47 4.72a.75.75 0 0 1 1.06 0l7.5 7.5a.75.75 0 1 1-1.06 1.06L12 6.31l-6.97 6.97a.75.75 0 0 1-1.06-1.06l7.5-7.5Z"
						clip-rule="evenodd"
					/>
				</svg>
				<!-- Leverage -->
			</div>
			<div class="navbar-item bg-slate-700">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="size-8"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
					/>
				</svg>
				<!-- Earn -->
			</div>
			<div class="navbar-item bg-slate-700">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					stroke-width="1.5"
					stroke="currentColor"
					class="size-8"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						d="M12 6.75a.75.75 0 1 1 0-1.5.75.75 0 0 1 0 1.5ZM12 12.75a.75.75 0 1 1 0-1.5.75.75 0 0 1 0 1.5ZM12 18.75a.75.75 0 1 1 0-1.5.75.75 0 0 1 0 1.5Z"
					/>
				</svg>

				<!-- More -->
				<!--(Stake, Redeem)-->
			</div>
		</div>

		<div class="hidden">
			<button class="h-[4rem] rounded-4xl bg-slate-700 px-4">
				<!-- <svg
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 24 24"
					fill="currentColor"
					class="size-8"
				>
					<path
						d="M2.273 5.625A4.483 4.483 0 0 1 5.25 4.5h13.5c1.141 0 2.183.425 2.977 1.125A3 3 0 0 0 18.75 3H5.25a3 3 0 0 0-2.977 2.625ZM2.273 8.625A4.483 4.483 0 0 1 5.25 7.5h13.5c1.141 0 2.183.425 2.977 1.125A3 3 0 0 0 18.75 6H5.25a3 3 0 0 0-2.977 2.625ZM5.25 9a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h13.5a3 3 0 0 0 3-3v-6a3 3 0 0 0-3-3H15a.75.75 0 0 0-.75.75 2.25 2.25 0 0 1-4.5 0A.75.75 0 0 0 9 9H5.25Z"
					/>
				</svg> -->

				0x268...0c2
			</button>
		</div>
	</div>

	<main>
		{@render children()}
	</main>
</div>

<style>
	@reference "../../../app.css";

	.navbar {
		@apply flex h-[4rem] w-full flex-row justify-stretch;
	}

	.navbar-item {
		@apply flex size-16 h-full items-center justify-center;
	}
</style>
