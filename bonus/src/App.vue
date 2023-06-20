<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppIcons from './components/AppIcons.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components:{
    AppHeader,
    AppMain,
    AppIcons,
    AppFooter
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppIcons />
  <AppFooter />
</template>

<style lang="scss">
  @use './styles/generals.scss' as *;
  @use './styles/partials/variables' as *;
</style>
