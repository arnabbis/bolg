<template>
<h1>For Loop Use</h1>
<ul>
<li v-for="item in fruits" :key="item">
{{item}}
</li>
</ul>
</template>


<script>
export default {
    name:"ForLoop",
    data(){
        return{
            fruits:["apple","banana","guava","grapes"],
        }
    }
}
</script>