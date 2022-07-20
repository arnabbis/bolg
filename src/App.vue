<template>
<img alt="Vue logo" src="./assets/logo.png">
<HelloWorld />
<EventWork/>
<MethodKey/>
<TwoWay/>
<CheckBox/>
<IfElse/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import EventWork from './components/Event.vue'
import MethodKey from './components/Methods.vue'
import TwoWay from './components/TwoWayBinding.vue'
import CheckBox from './components/CheckBox.vue'
import IfElse from './components/IfElse.vue'

export default {
    name: 'App',
    components: {
        HelloWorld,
        EventWork,
        MethodKey,
        TwoWay,
        CheckBox,
        IfElse,
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
