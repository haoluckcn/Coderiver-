<template>
  <div id="app">
    <div id="nav">
      <router-link to="/login">登陆</router-link> |
      <router-link to="/sigin">注册</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@import './assets/css/reset.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
