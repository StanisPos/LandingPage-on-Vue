<template lang="pug">
  div.search
    svg.search__icon(width="15" height="19" viewBox="0 0 15 19" fill="none" xmlns="http://www.w3.org/2000/svg")
      path(fill-rule="evenodd" clip-rule="evenodd" d="M7.13463 18.0769C7.13463 18.0769 14.0769 12.2308 14.0769 7.48076C14.0769 3.64663 10.9688 0.538452 7.13463 0.538452C3.3005 0.538452 0.192322 3.64663 0.192322 7.48076C0.192322 12.5961 7.13463 18.0769 7.13463 18.0769ZM7.1346 10.0385C8.95077 10.0385 10.4231 8.56616 10.4231 6.74999C10.4231 4.93383 8.95077 3.46153 7.1346 3.46153C5.31843 3.46153 3.84614 4.93383 3.84614 6.74999C3.84614 8.56616 5.31843 10.0385 7.1346 10.0385Z")
    input.search__input(type="text" placeholder="Find your place here")
    button.search__button(type="submit")
      svg.search__button-icon(width="32" height="31" viewBox="0 0 32 31" xmlns="http://www.w3.org/2000/svg")
        path(fill-rule="evenodd" clip-rule="evenodd" d="M19.5925 11.2962C19.5925 15.8781 15.8781 19.5925 11.2962 19.5925C6.71435 19.5925 3 15.8781 3 11.2962C3 6.71435 6.71435 3 11.2962 3C15.8781 3 19.5925 6.71435 19.5925 11.2962ZM18.4865 20.009C16.5332 21.6228 14.0279 22.5925 11.2962 22.5925C5.0575 22.5925 0 17.535 0 11.2962C0 5.0575 5.0575 0 11.2962 0C17.535 0 22.5925 5.0575 22.5925 11.2962C22.5925 13.7211 21.8285 15.9674 20.528 17.8078L31.0496 28.3294L28.9283 30.4507L18.4865 20.009Z")


</template>

<script></script>

<style lang="stylus">
  .search
    display: flex
    justify-content: space-between
    align-items: center
    min-width: 475px
    height: 62px
    padding-left: 30px
    padding-right: 4px
    border-radius: 31px
    background-color: #ffffff

  .search__icon
    fill: #13F1FC

  .search__input
    font-family: 'Cabin'
    font-size: 19px
    line-height: normal
    flex-grow: 1
    margin-left: 20px
    border: none
    outline: none
    &::placeholder
      color: #BDD3DF


  .search__button
    position: relative
    width: 88px
    height: 54px
    background-color: #13F1FC
    border: none
    border-radius: 50px
    outline: none

  .search__button-icon
    position: absolute
    top: 50%
    left: 50%
    transform: translate(-50%, -50%)
    fill: #ffffff
</style>
