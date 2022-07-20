<template>
<!-- <h1 v-on:mouseover="getData()"><u>WELCOME TO MY CODE AND DO SOMETHING INTERESTING</u></h1> -->
<h2 v-on:mouseover="getConsole()"><u>VUE.JS TUTORIAL</u></h2>
<button v-on:click="onClick()">Click Here</button>
<button v-on:dblclick="onClick()">Click Here</button>
<h2>{{count}}</h2>
</template>

<script>
export default {
    name:"EventWork",
    data(){
        return{
            count:0,
        }
    },
    methods: {
        onClick(){
            this.count = this.count+1
            return alert("HII MY NAME IS ARNAB")
        },
        getData(){
            return alert("WELCOME TO VUE.JS")
        },
        getConsole(){
            return console.warn("Enter your name")
        }
    },
}
</script>