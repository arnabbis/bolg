<template>
<div>
<h1>CHECKBOX AND RADIO BUTTON</h1>
<h2>NEW CODING LANGUAGE</h2>
<label for="java">Java</label>
<input type="checkbox" value="java" v-model="technology" id="java"/>
<label for="python">Python</label>
<input type="checkbox" value="python"  v-model="technology" id="python"/>
<label for="javascript">Javascript</label>
<input type="checkbox" value="javascript" v-model="technology"  id="javascript"/>
<h3>SELECTED TECHNOLOGY: {{technology}}</h3>

<h2>NEW CODING LANGUAGE</h2>
<label for="java">Java</label>
<input type="radio" value="java"  name="codingLanguage" v-model="codingLanguage" id="java"/>
<label for="python">Python</label>
<input type="radio" value="python" name="codingLanguage" v-model="codingLanguage" id="python"/>
<label for="javascript">Javascript</label>
<input type="radio" value="javascript" name="codingLanguage" v-model="codingLanguage"  id="javascript"/>
<h3>SELECTED TECHNOLOGY: {{codingLanguage}}</h3>
</div>
</template>

<script>
export default{
    name:"CheckBox",
    data(){
        return{
            technology:[],
            codingLanguage:null,
        }
    }
}
</script>