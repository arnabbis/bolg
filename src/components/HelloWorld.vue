<template>
  <div class="hello">
  <h1>Hello Welcome</h1>
  <CompoNents/>
  <ProductData/>
  </div>
</template>

<script>
// import Components from './components.vue';
import CompoNents  from "./components.vue";
import ProductData  from "./product.vue";

export default {
  name: 'HelloWorld',
    components:{
      CompoNents,
      ProductData,

    },
}
</script>

<style scoped>
div{
  background-color:aquamarine;
  height: 500px;
}
</style>

