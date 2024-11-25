<script>
	let units = [1, 2, 3, 4]
</script>
<svelte:head>
	<title>Gallery</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="text-column">
	{#each units as unit }
		
		<div style='margin-bottom: 30px'>
			<h1>Unit {unit}</h1>
			no writings are here yet!
		</div>

	{/each}
</div>

