<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Home from '@/views/Home.vue'
export default {
  name: 'App',
  components: {
      Header,
      Home,
  }
}
</script>

<style>
#app {
  font-family: 'Libre Franklin', 'Helvetica Neue', helvetica, arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

html, body, ul, li, nav {
  padding: 0;
  margin: 0;
  font-size:10px;
}

img {
  -webkit-user-drag: none;
  -khtml-user-drag: none;
  -moz-user-drag: none;
  -o-user-drag: none;
  user-drag: none;
}

</style>
