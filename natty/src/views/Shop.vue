<template>
  <div class="main">
    

    <div class="banners">
      <div class="paragraphTitles">
        <h2>SHOP</h2>
      </div>
        
      <div class="left">

      <h1>DIGITAL - CERAMIC</h1>
      <h1>CLOTHING</h1>
      <h1>BOOKS</h1>
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
 padding-top: 100px;
    background-image: linear-gradient(to bottom , rgb(88, 163, 182), rgb(91, 222, 255));
margin-top: -100px;
  height: 1000px;
  width: 100%;
}
.banners{

 height: 500px;
        width: 1200px;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  padding: 20px 20px 20px 20px;
  margin-bottom: 40px;


}
.left{
  margin-top: 100px;
  width: 600px;
  height: 100px;
  padding-left: 0px;
}
.left h1{
  font-size: 50px;
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
  z-index: 0;
  position: absolute;
  margin-left: -100px;
}
#boos{
  height: 150px;
  width: 150px;
  position: absolute;
  margin-left: 80px;
  margin-top:160px;
  z-index: 1;
}
.paragraphTitles{
  background-color: tan;
  padding-top: 10px;
  height: 50px;
  border-radius: 50px;
}
</style>