<script>
import AppHeaderVue from './components/AppHeader.vue'
import AppMainVue from './components/AppMain.vue'
import AppBlueStringVue from './components/AppBlueString.vue'
import AppFooterVue from './components/AppFooter.vue'

export default {
  components: {
    AppHeaderVue,
    AppMainVue,
    AppBlueStringVue,
    AppFooterVue
  }
}
</script>

<template >
  <AppHeaderVue />
  <AppMainVue />
  <AppBlueStringVue />
  <AppFooterVue />
</template>

<style lang="scss">

</style>