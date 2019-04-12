<template lang="pug">
  div.logo__wrapper
    .icon__wrapper
      svg.icon(width="19" height="24" viewBox="0 0 19 24" fill="none" xmlns="http://www.w3.org/2000/svg")
        path(fill-rule="evenodd" clip-rule="evenodd" d="M9.5 24C9.5 24 19 16 19 9.5C19 4.25329 14.7467 0 9.5 0C4.25329 0 0 4.25329 0 9.5C0 16.5 9.5 24 9.5 24ZM9.5 13C11.9853 13 14 10.9853 14 8.5C14 6.01472 11.9853 4 9.5 4C7.01472 4 5 6.01472 5 8.5C5 10.9853 7.01472 13 9.5 13Z")
      svg.ellipse(width="26" height="7" viewBox="0 0 26 7" xmlns="http://www.w3.org/2000/svg")
        ellipse(cx="13" cy="3.5" rx="13" ry="3.5")
    p.logo__text CityMap

</template>

<script></script>

<style lang="stylus">
  .logo__wrapper
    min-width: 100px
  .logo__wrapper,
  .icon__wrapper
    display: flex
    align-items: center
  .icon__wrapper
    flex-direction: column
    flex-grow: 1
  .icon
    fill: #ffffff
  .ellipse
    fill: #ffffff
    opacity: 0.2
  .logo__text
    font-family: 'Cabin'
    font-size: 19px
    line-height: normal
    font-weight: bold
    color: #ffffff
</style>