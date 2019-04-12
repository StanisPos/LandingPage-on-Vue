<template lang="pug">
  .content__wrapper
    .content__search-wrapper
      h1.content__title Search Your Destination
      p.content__text Then select departure date, how long the trip will be and how many destinations to include. Users can also select if they want to look at cities in Europe, the European Union or just the Schengen Zone. 
      Search
    .content__image-wrapper

</template>

<script>
  import Search from '@/components/Search.vue'

  export default {
    name: 'content-template',
    components: {
      Search
    }
  }
</script>

<style lang="stylus">
  .content__title
    font-family: 'GilroyBold'
    font-size: 50px
    line-height: normal
    color: #ffffff
  .content__text
    font-family: 'Cabin'
    font-size: 16px
    line-height: 25px
    color: #B7E6FF
</style>
