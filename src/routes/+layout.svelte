<script>
	import '../app.postcss';
</script>

<svelte:head>
	<title>Thank You</title>
</svelte:head>

<div class="bg-[url('SPL_BG.webp')] bg-cover bg-fixed min-h-full min-w-full ">
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
