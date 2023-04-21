<script>
	import { createEventDispatcher } from 'svelte';

	const eventOut = createEventDispatcher();

	function clickEvent() {
		eventOut('click');
	}
	/** @type{'purple'|'pink'|'yellow'|'green'|'red' } */
	export let color = 'purple';
</script>

<button on:click={clickEvent} class={color}>
	<slot />
</button>

<style>
	button {
		padding: 8px 24px;
		border-width: 2px;
		border-style: solid;

		cursor: pointer;
	}
	button.purple {
		background-color: var(--color-purple);
	}
	button.pink {
		background-color: var(--color-pink);
	}
	button.yellow {
		background-color: var(--color-yellow);
	}
	button.green {
		background-color: var(--color-green);
	}
	button.red {
		background-color: var(--color-red);
	}
</style>
