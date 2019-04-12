<template lang="pug">
  header.navigation__wrapper
    Logo
    nav.header__navigation
      ul.header__navigation-list
        li.header__navigation-item(v-for="item in navs")
          a.header__navigation-link(href="#") {{ item.key }}

</template>

<script>
  const navigation = [
    { key: 'About us' },
    { key: 'Find Place' },
    { key: 'City Map' },
    { key: 'Contact' },
  ]

  import Logo from '@/components/Logo'


  export default {
  name: 'navigation',
  components: {
    Logo
  },
  data: () => {
    return {
      navs: navigation
    }
  },
  mounted(){
  }
}
</script>

<style lang="stylus" scoped>
  .navigation__wrapper
    display: flex
    justify-content: space-between
    align-items: center
    margin-bottom: 150px
  .header__navigation
    min-width: 390px
  .header__navigation-list
    display: flex
    justify-content: space-between
    margin: 0
    padding: 0
    list-style-type: none
  .header__navigation-link
    font-family: 'Cabin'
    font-size: 18px
    letter-spacing: 0.05em
    line-height: normal
    text-align: left
    color: #ffffff
    text-decoration: none
</style>
