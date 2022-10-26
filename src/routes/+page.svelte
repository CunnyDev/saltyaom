<script lang="ts">
	const proofs: [
		{
			link: string;
			img: string;
		}
	] = [
		{
			link: 'https://twitter.com/saltyAom/status/1584456558536105984',
			img: 'https://media.discordapp.net/attachments/1034868245750108310/1034868371709247680/unknown.png?width=1138&height=1138'
		},
		{
			link: '',
			img: 'https://media.discordapp.net/attachments/1034868245750108310/1034868811561717810/unknown.png?width=1518&height=1139'
		},
		{
			link: '',
			img: 'https://media.discordapp.net/attachments/1034868245750108310/1034868986829086760/unknown.png?width=854&height=1139'
		}
	];
</script>

<h1 class="text-2xl">
	Proofs that <a class="text-sky-500 underline" href="https://github.com/saltyaom">SaltyAom</a> is 😭
</h1>
<div class="grid grid-cols-2 md:grid-cols-3 xl:grid-cols-4 gap-3 w-full">
	{#each proofs as proof}
		<a
			href={proof.link || '#'}
			class="w-full h-full aspect-square bg-gray-400 hover:shadow-md border-2 border-black transition-all"
		>
			<img src={proof.img} alt="" class="w-full h-full object-cover" />
		</a>
	{/each}
</div>
