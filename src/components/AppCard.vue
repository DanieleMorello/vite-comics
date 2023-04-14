<script>
  export default {
  name: 'AppCard',
  props: {
    image: String,
    title: String
  },
}
</script>
<template>
  <div class="col">
    <div class="product">
      <img :src="image" :alt="title">
      <h4>{{ title }}</h4>
    </div>
  </div>
</template>

<style>

</style>