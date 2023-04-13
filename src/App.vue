<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {

    }
  }
} 
</script>

<template>
  <div class="">
    <AppHeader></AppHeader>
    <AppMain></AppMain>
    <AppFooter></AppFooter>
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