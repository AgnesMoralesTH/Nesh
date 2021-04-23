<template>
 <div class="main">
    <Me />
    <Art />
    <Shopmini />
  </div>
</template>

<script>
// @ is an alias to /src
import Me from '../components/homeCom/Me'
import Art from '../components/homeCom/Art'
import Shopmini from '../components/homeCom/Shopmini'


export default{
  components: {
    Me,
    Art,
    Shopmini,
  },

}
</script>

<style scoped>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Fira Sans', sans-serif;
}
.main{
 padding-top: 100px;
    background-image: linear-gradient(to bottom , rgb(232, 250, 255), rgb(255, 241, 224));
margin-top: -100px;
  height: 100%;
  width: 100%;
}

.home{
  padding-top: 100px;

  height: 100%;
  width: 100%;
  
    background-image: linear-gradient(to bottom , rgb(232, 250, 255), rgb(255, 241, 224));

margin-top: -100px;
  margin: 0 auto;
  
}
</style>
