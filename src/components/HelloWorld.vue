<template>
  <div class="hello">
  <h1>Hello Welcome</h1>
  <CompoNents/>
  <ProductData/>
  <TemPlate/>
  </div>
</template>

<script>
// import Components from './components.vue';
import CompoNents  from "./components.vue";
import ProductData  from "./product.vue";
import TemPlate from "./templates.vue";
export default {
  name: 'HelloWorld',
    components:{
      CompoNents,
      ProductData,
      TemPlate,

    },
}
</script>

<style scoped>
div{
  background-color:aquamarine;
  height: 500px;
}
</style>

