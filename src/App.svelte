<script lang="ts">
	import Tailwindcss from './Tailwindcss.svelte';

	export let name: string;
</script>

<Tailwindcss />
<main class="md:max-w-[240px] text-center p-4 mx-auto">
	<h1 class="text-red-500 uppercase font-thin text-7xl">Hello {name}!</h1>
	<p>This is a starting place for my personal page.</p>
</main>
