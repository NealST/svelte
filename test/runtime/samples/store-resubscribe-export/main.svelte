<script>
	import { writable } from 'svelte/store';
	export let foo = writable(0);
</script>

<h1>{$foo}</h1>
