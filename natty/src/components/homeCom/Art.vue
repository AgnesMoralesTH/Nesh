<template>
    <div class="homeSecond">
    <div class="top">
        <h1>ART</h1>
        <p>only the best</p>
    </div>


   <div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
    </div>
    
    </div>
    
</template>



<style scoped>
    .homeSecond{
        height: 600px;
        width: 900px;
        
        
        margin: 0 auto;
        padding: 20px 20px 20px 20px;
          background-image: linear-gradient(to bottom left, rgb(255, 234, 237), rgb(229, 153, 165));

    }
    .top{
        height:100px;
        width: 300px;
        
    }
        .left{
  line-height: 10px;
}
    
    .top h1, p{
        display: inline;
        
        margin-left: 20px;
    }
    .grid-container{
        width: 700px;
        height: 300px;
       display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  background-color: #2196F3;
  margin: 0 auto;
    }
    .grid-item{
      background-color: white;
      padding: 10px;
      border: 2px solid silver;
    }
</style>