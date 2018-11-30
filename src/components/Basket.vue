<template>
  <div class="basket">
    <h2>{{title}}</h2>
    <h3>Start to add basket-related components here.</h3>
  </div>
</template>

<script>
import basketData from '../data/basket.js'
export default {
  name: 'basket',
  props: [ 'title' ],
  data () {
    return {
      basket: basketData
    }
  }
}
</script>

<style>
.basket {
  border: 2px solid red;
}
</style>
