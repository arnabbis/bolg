<template>
  <div>
    <h1>My name is {{name}}</h1>
    <button @click="changeName('arnab')">Click To Change</button>
  </div>
</template>

<script>
export default {
    name:"TemPlate",
    methods: {
        changeName(name){
             alert(name);
        }
    },
}
</script>

<style>

</style>