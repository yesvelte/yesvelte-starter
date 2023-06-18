<script>
	import tabler from 'yesvelte/css/tabler.min.css?url';
	import daisyui from 'yesvelte/css/daisyui.min.css?url';

	// you can change theme of your project from here.
	let theme = 'tabler';
	// let theme = 'daisyui';
</script>

<svelte:head>
	{#if theme === 'tabler'}
		<link rel="stylesheet" href={tabler} />
	{:else}
		<link rel="stylesheet" href={daisyui} />
	{/if}
</svelte:head>

<slot />
