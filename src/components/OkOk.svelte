<script lang="ts">
import { getContext } from 'svelte';
	import { COUNTER_CONTEXT } from './const';

	const context = getContext(COUNTER_CONTEXT)

</script>


<div>
  {context?.hundrad || "CAN NOT GET CONTEXT"}
</div>