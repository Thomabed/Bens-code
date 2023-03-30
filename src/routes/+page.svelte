<script>
	import { src_url_equal } from "svelte/internal";
	import Questions from "../components/questions.svelte";
	import Score from "../components/score.svelte";

</script>
    <Score score={14} />


    <Questions 
    number= {1}  
     answer1="First answer"
     answer2="Second answer"
     answer3="Third answer"
     answer4="All of the above"
>
This is my new Question? 

</Questions>
<button id="my-button">My Button</button>
<button id="your-button">Your Button</button>
