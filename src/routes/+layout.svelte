
<script>
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();

	let menuOpen = $state(false);
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<link rel="stylesheet" href="/css/main.css">
</svelte:head>


<header class="header">
	<div class="container">

		<h1 class="header-logo">
			<a href="/">株式会社シモトリ電気</a>
		</h1>

		<button
			class="menu-button"
			class:open={menuOpen}
			onclick={() => menuOpen = !menuOpen}
			aria-label="メニューを開く"
			aria-expanded={menuOpen}
		>
			<span></span>
			<span></span>
			<span></span>
		</button>

		<nav class:open={menuOpen}>
			<a href="/company" onclick={() => menuOpen = false}>
				会社概要
			</a>

			<a href="/works" onclick={() => menuOpen = false}>
				施工事例
			</a>

			<a href="/#contact" onclick={() => menuOpen = false}>
				お問い合わせ
			</a>
		</nav>

	</div>
</header>

{@render children()}

<footer>
	<p>© 2026 株式会社シモトリ電気</p>
</footer>