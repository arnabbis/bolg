<template>
<img src="./assets/logo.png" alt="Arnab">
<h1>MY NAME IS ARNAB BISWAS</h1>

<MyCode/>
<HomePage />
</template>

<script>
import HomePage from './components/Home.vue'
import MyCode from './components/MyCode.vue'
export default {
    name: 'App',
    components: {

        HomePage,
        MyCode,
    }
}
</script>
