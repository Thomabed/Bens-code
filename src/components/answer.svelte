<script>
    export let answer = false;
 </script>

 {#if answer}
 <p class = correct  >Great job!</p>
 {:else}
 <p class = incorrect >Not quite...</p>
 {/if}
<p>
     <style>
    .correct {
        color:green; 
        font-weight:italic;
    }
 </style>
  </p>
  <p>
  <style>
    .incorrect {
        color:Red; 
        font-weight:bold;
    }
  </style>
  </p>
