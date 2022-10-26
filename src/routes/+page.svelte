<script lang="ts">
	const proofs: [
		{
			link: string;
			img: string;
		}
	] = [
		{
			link: '',
			img: ''
		},
		{
			link: '',
			img: ''
		},
		{
			link: '',
			img: ''
		}
	];
</script>

<h1 class="text-2xl">Proofs that <a href="https://github.com/saltyaom">Saltyaom</a> is 😭</h1>
<div class="grid grid-cols-2 md:grid-cols-3 xl:grid-cols-4 gap-3 w-full">
	{#each proofs as proof}
		<div class="w-full h-full aspect-square bg-gray-400">
			<img src={proof.img} alt="" />
		</div>
	{/each}
</div>
