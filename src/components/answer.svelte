<script>
	export let answer = true;
</script>
{#if answer}
	<p class="correct">Good job!</p>
{:else}
	<p class="incorrect">Not quite...</p>
{/if}
<style>
	.correct,
	.incorrect {
		font-weight: bold;
		text-decoration: underline;
	}
	.correct {
		color: green;
	}
	.incorrect {
		color: red;
	}
</style>