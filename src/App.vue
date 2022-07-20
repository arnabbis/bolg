<template>
<img alt="Vue logo" src="./assets/logo.png">
<HelloWorld/>
<MyCode/>
<HomePage/>
<MethodKey/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HomePage from "./components/Home.vue";
import MyCode from "./components/MyCode.vue";
import MethodKey from "./components/Methods.vue";

export default {
    name: 'App',
    components: {
        HelloWorld,
        HomePage,
        MyCode,
        MethodKey,
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
