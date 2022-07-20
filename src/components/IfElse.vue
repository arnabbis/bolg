<template>
    <h1 v-if="show">IF CONDITION</h1>
    <!-- <h1 v-else>ELSE CONDITION </h1> -->
    <button v-on:click="show=!show">CLICK ME</button>
</template>



<script>
export default{
    name : "IfElse",
    data(){
        return{
            show:true,
        }
    }
}
</script>