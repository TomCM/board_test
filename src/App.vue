<template>
  <div id="nav">
    <router-link to="/">My Board 修改 12</router-link>
    <router-link to="/">My Board branch 1</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/about">About branch marster</router-link>
  </div>
  <router-view/>
</template>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
</style>
