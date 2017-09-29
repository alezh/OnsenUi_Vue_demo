<template>
<v-ons-page id="app">
    <header-top></header-top>
    <div class="content">
      <img src="./assets/logo.png">
      <router-view></router-view>
    </div>
    <food-bottom></food-bottom>
</v-ons-page>
</template>
<script>
import headerTop from './layout/Header'
import foodBottom from './layout/Fooder'

export default {
  name: 'app',
  components:{
        headerTop,foodBottom
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  background: #efeff4;
}
</style>
