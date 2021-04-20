<template>
 <div class="home">
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
.home{
  background-color: silver;

  margin: 0 auto;
  padding: 20px 20px 20px 20px;
}
</style>
