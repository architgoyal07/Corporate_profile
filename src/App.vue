<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->

      <home/>

    <router-view />
  </div>
</template>

<script>

  import Home from './components/Home'

export default {
  name:'app',
  components:{
    Home
  }
}
</script>

<style>

*{
  box-sizing: border-box;
  margin:0px;
  padding: 0px;
}


#app {
  font-family: 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-color: #080808;
}



/* #nav {
   padding: 30px;

   a {
     font-weight: bold;
     color: #2c3e50;

     &.router-link-exact-active {
       color: #42b983;
     }
   }
 }*/


</style>
