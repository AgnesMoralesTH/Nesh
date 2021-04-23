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
ul {
  list-style-type: none;
  font-weight: 200;
  font-size: 20px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-align: center;
}

#nav li:active {
  border: 2px solid black;
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

