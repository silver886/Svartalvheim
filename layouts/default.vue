<template>
  <div>
    <nuxt/>
  </div>
</template>

<style lang="sass">
@import url('https://fonts.googleapis.com/css?family=Roboto:300,500')
@import url('https://fonts.googleapis.com/css?family=Staatliches')
@import '../sass/colors.sass'

html
  font-family: 'Roboto', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif
  font-size: 16pt
  font-weight: 100
  word-spacing: 1pt
  -ms-text-size-adjust: 100%
  -webkit-text-size-adjust: 100%
  -moz-osx-font-smoothing: grayscale
  -webkit-font-smoothing: antialiased
  box-sizing: border-box
  background-color: $grey-900

*, *:before, *:after
  box-sizing: border-box
  margin: 0

::-webkit-scrollbar
  width: 0px
  background: transparent

/* optional: show position indicator in red */
::-webkit-scrollbar-thumb
  background: #FF0000
</style>

