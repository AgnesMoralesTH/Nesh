<template>
  <div id="nav">
    <TheNavigation />
    

  </div>
  <router-view />
</template>

<style>
#app {
  font-family:'Yantramanav', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  height: 60px;
   margin: 0 auto; 
    text-align: center;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

<script>
import TheNavigation from './components/TheNavigation'

export default{
  components: {
    TheNavigation
  }
}
</script>

