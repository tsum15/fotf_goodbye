<script>
	import '../app.postcss';
	import { dev } from '$app/environment';
	import { inject } from '@vercel/analytics';
	inject({ mode: dev ? 'development' : 'production' });
</script>

<svelte:head>
	<title>Thank You</title>
</svelte:head>

<div>
	<div class="container mx-auto">
		<header class="pb-8">
			<img
				src="SPL_stacked_no_bg.webp"
				alt="Stay and Play Local logo"
				class="max-w-[85%] md:max-w-[55%] mx-auto pt-8"
			/>
		</header>
		<slot />
	</div>
</div>
