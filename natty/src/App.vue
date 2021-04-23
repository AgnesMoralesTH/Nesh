<template>
<div id="app">
  <div id="nav">
    <TheNavigation />
    

  </div>
  <router-view />
  </div>
</template>

<style>
#app {
  font-family:'Yantramanav', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height:100%;
  
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


</style>

<script>
import TheNavigation from './components/TheNavigation'

export default{
  components: {
    TheNavigation
  }
}
</script>

