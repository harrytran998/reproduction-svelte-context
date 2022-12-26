<script lang="ts">
	import { setContext } from 'svelte';
	import { COUNTER_CONTEXT } from './const';
	function hello() {
		console.log('Hello');
	}

	const hundrad = 100;
	setContext(COUNTER_CONTEXT, {
		hello,
		hundrad
	})

</script>

<slot />