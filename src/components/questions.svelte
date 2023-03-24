<script>
    export const number = 1

export let answer1 = "";
export let answer2 = "";
export let answer3 = "";
export let answer4 = "";
</script>

<div>
    <p> {number}. <slot/></p>

    <label for="q{number}a">
        <input 
        type="radio" 
        name="q{number}" 
        id="q{number}a"
        value="a"
        />
        A:{answer1}
    </label>

<label for="q{number}b">
    <input 
    type="radio" 
    name="q{number}" 
    id="q{number}a"
    value="b"
    />
    B:{answer2}
</label> 

<label for="q{number}c">
    <input 
    type="radio" 
    name="q{number}" 
    id="q{number}a"
    value="c"
    />
    C:{answer3}
</label> 

<label for="q{number}d">
    <input 
    type="radio" 
    name="q{number}" 
    id="q{number}a"
    value="a"
    />
    D:{answer4}
</label>
</div>