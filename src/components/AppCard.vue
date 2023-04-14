<script>
export default {
  name: 'AppCard',
  props: {
    thumb: String,
    price: String,
    series: String,
    type: String,
  },
}
</script>
<template>
  <div class="col">
    <div class="product">
      <img :src="thumb" :alt="series">
      <h4>{{ series }}</h4>
    </div>
  </div>
</template>

<style lang="scss" scoped>
h4 {
  text-transform: uppercase;
}
</style>