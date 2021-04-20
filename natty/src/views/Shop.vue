<template>
  <div class="main">
    

    <div class="banners">
      <div class="left">
        <h5>SHOP</h5>

      <h1>DIGITAL - CERAMIC - <br/> CLOTHING - <br/> BOOKS</h1>
      </div>
      
      <div class="right">
        <img src="../assets/pook.png" alt="" id="pook">
        <img src="../assets/boos.png" id="boos">
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Fira Sans', sans-serif;
}
.main{
  background-color: rgb(117, 204, 175);
  height: 1000px;
  width: 100%;
}
.banners{
 margin-top: 20px;
 height: 500px;
        width: 900px;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  padding: 20px 20px 20px 20px;
  margin-bottom: 40px;


}
.right{
  background-image: linear-gradient(to bottom left, rgb(255, 234, 237), rgb(229, 153, 165));
  height: 500px;
  width: 500px;
  border-radius: 50%;
}
#pook{
  height: 400px;
  width: 400px;
  z-index: 2;
  position: absolute;
  margin-left: -100px;
}
#boos{
  height: 400px;
  width: 400px;
  position: absolute;
  margin-left: -200px;
  z-index: 1;
}
</style>