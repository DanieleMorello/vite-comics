<script>
import AppHeader from "./components/AppHeader.vue"
import AppJumbotron from "./components/AppJumbotron.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"

export default {
  components: {
    AppHeader,
    AppJumbotron,
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
  <AppHeader></AppHeader>
  <AppJumbotron></AppJumbotron>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
.row {
  margin-right: 0;
}
</style>