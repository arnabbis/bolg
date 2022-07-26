<template>
<div>

<!-- <img alt="Vue logo" src="./assets/logo.png"> -->
<HelloWorld />
<!-- <components/> -->
<EventWork/>
<MethodKey/>
<TwoWay/>
<!-- <CheckBox/> -->
<IfElse/>
<ForLoop  data="Arnab Biswas"  msg="I am from westbengal"/>
</div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

// import EventWork from './components/Event.vue'
// import MethodKey from './components/Methods.vue'
// import TwoWay from './components/TwoWayBinding.vue'
// // import CheckBox from './components/CheckBox.vue'
// import IfElse from './components/IfElse.vue'
// import ForLoop from './components/ForLoop.vue'



export default {
    name: 'App',
    components: {
    HelloWorld,
    // components,
    // EventWork,
    // MethodKey,
    // TwoWay,
    // // CheckBox,
    // IfElse,
    // ForLoop,
    
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
