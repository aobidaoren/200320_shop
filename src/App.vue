<template>
  <div id="app">
      <router-view></router-view>
      <FooterGulde v-show="$route.meta.showFooter"/>
  </div>
</template>

<script>
import FooterGulde from './components/FooterGuide/FooterGulde.vue'
export default {
    components:{
        FooterGulde
    }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
.app
    width 100%
    height 100%
    background-color #f5f5f5
    position relative
</style>