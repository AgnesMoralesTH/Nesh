<template>
 <div class="home">
    <Me />
    <Art />

  </div>
</template>

<script>
// @ is an alias to /src
import Me from '../components/homeCom/Me'
import Art from '../components/homeCom/Art'
export default{
  components: {
    Me,
    Art
  },

}
</script>

<style scoped>
<style scoped>
.home{
  background-color: silver;

  margin: 0 auto;
  padding: 20px 20px 20px 20px;
}
</style>
