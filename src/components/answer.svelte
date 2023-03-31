<script>
    export let answer = false;
 </script>

 {#if answer}
 <p style = "color:green;">Great job</p>
 {:else}
 <p style = "color:red;">not quite...</p>
 {/if}
  