<template>
    <div class="homeSecond">

    <div class="top">
        <h1>CERAMICS</h1>
        
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
        height: 750px;
        width: 1100px;
        
        
        margin: 0 auto;
        padding: 20px 20px 20px 20px;

    }
    .top{
        height:50px;
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
        width: 1000px;
        height: 650px;
       display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 2fr 2fr;
  margin: 0 auto;
  grid-gap: 10px;
    }
    .grid-item{
      background-color: white;
      padding: 10px;
      border: 2px solid silver;
    }
</style>