<script>
    export let answer = false;
 </script>

 {#if answer}
 <p class = correct  >Great job</p>
 {:else}
 <p style = "color:red;">not quite...</p>
 {/if}

 <style>
    .correct {
        color:green; 
        font-weight:bold;
    }
    
 </style>
  