<script>
	import Github from '../component/icon/Github.svelte';
</script>

<div class="flex h-screen flex-col">
	<div class="pt-6">
		<h1 class="text-center text-3xl font-bold">Ali Ahad</h1>
		<h3 class="text-center text-xl">Full Stack Developer!</h3>
	</div>
	<div class="flex justify-center p-1">
		<a class="p-1" href="https://www.github.com/iamAliahad">
			<Github />
		</a>
	</div>
</div>

<!-- you can pass class (or anything else) using $$restProps -->

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
