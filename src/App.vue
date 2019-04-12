<template>
  <div id="app">
    <Introduction />
    <Started />
    <Payments />
    <Hospital />
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
  </div>
</template>
<script>
// @ is an alias to /src
import Fonts from '@/components/Fonts'
import Introduction from '@/modules/Introduction'
import Started from '@/modules/Started'
import Payments from '@/modules/Payments'
import Hospital from '@/modules/Hospital'

export default {
  name: 'basic-template',
  components:{
    Fonts,
    Introduction,
    Started,
    Payments,
    Hospital
  }
}
</script>

<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50

#nav
  padding 30px
  a
    font-weight bold
    color #2c3e50
    &.router-link-exact-active
      color #42b983
</style>
