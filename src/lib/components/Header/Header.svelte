<script>
	import ContentLayout from '$lib/utils/ContentLayout.svelte';
	const handleClick = () => {
		document.getElementById('dream')?.scrollIntoView({ behavior: 'smooth' });
	};
</script>

<section class="">
	<ContentLayout>
		<section class="flex text-white md:flex-row flex-col px-10 justify-center">
			<img
				class=" md:max-w-[30rem] md:order-1 order-2 lg:max-w-[48rem]"
				src="router2.png"
				alt="marting router "
			/>
			<div
				class="flex w-full flex-col pb-16 md:py-0 order-1 md:order-2 items-center md:items-end gap-20 sm:gap-40"
			>
				<h1 class="uppercase mt-28 font-bold text-4xl md:text-3xl lg:text-5xl">
					Martin $Router King
				</h1>
				<button
					on:click={handleClick}
					class="outline-2 md:ml-auto outline px-7 py-2 rounded-full text-base lg:text-lg hover:bg-black hover:text-white"
					>Let's Begin</button
				>
			</div>
		</section>
	</ContentLayout>
</section>
