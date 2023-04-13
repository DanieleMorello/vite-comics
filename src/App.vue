<script>
import AppHeader from "./components/AppHeader.vue"
export default {
  components: {
    AppHeader
  }
} 
</script>

<template>
  <div class="debug">
    <AppHeader></AppHeader>
    <main></main>
    <footer>
      <div class="footer_top"></div>
      <div class="footer_bottom"></div>
    </footer>
  </div>
</template>

<style lang="scss">
.debug {
  header {
    height: 122px;
    background-color: #b1b2b5;
  }

  main {
    height: 129px;
    background-color: #7e2b97;
  }

  footer {
    .footer_top {
      height: 365px;
      background-color: #3a59b8;
    }

    .footer_bottom {
      height: 103px;
      background-color: #841a56;
    }
  }

}
</style>