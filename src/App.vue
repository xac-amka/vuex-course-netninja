<template>
  <div id="app">
    <ProductListOne />
    <ProductListTwo />
  </div>
</template>

<script>
import ProductListOne from './components/ProductListOne'
import ProductListTwo from './components/ProductListTwo'
export default {
  name: 'app',
  components : {
    ProductListOne,
    ProductListTwo
  },
  data () {
    return {
      
    }
  }
}
</script>

<style>
body {
  font-family: Ubuntu;
  color: #555555;
}
</style>
