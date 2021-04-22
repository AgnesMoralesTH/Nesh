<template>
    <div class="homeSecond">

    <div class="top">
        <h1 class="paragraphTitles">DIGITAL ARTS</h1>
        
    </div>


   <div class="grid-container">
  <div class="grid-item">
      <img src="../../assets/IMG_2906.png" alt="">
      
    </div>
  <div class="grid-item">
      <img src="../../assets/IMG_1558.png"  class="grid1" alt="">
    </div>
  <div class="grid-item">
      <img src="../../assets/IMG_1783.png"  class="grid1" alt="">
      </div>
  <div class="grid-item">
      <img src="../../assets/IMG_2899.png"  class="grid1" alt="">
      </div>
  <div class="grid-item">
      <img src="../../assets/IMG_2907.png"  class="grid1" alt="">
      </div>
  <div class="grid-item">
      <img src="../../assets/IMG_2908.png"  class="grid1" alt="">
      </div>
  <div class="grid-item">
      <img src="../../assets/IMG_2909.png"  class="grid1" alt="">
      </div>
  <div class="grid-item"></div>
    </div>
    
    </div>
    
</template>



<style scoped>
.grid-item{
    cursor: pointer;
   
}


img{
    height: 100%;
    width: 100%;
    
}
.paragraphTitles{
  background-color: tan;
  padding-top: 10px;
  height: 100px;
  width: 100px;
  border-radius: 50px;
}


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
        background-image: repeating-radial-gradient(to bottom left, blue to green);
        width: 1000px;
        height: 500px;
       display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  margin: 0 auto;
  grid-gap: 10px;
    }
    .grid-item{
      background-color: white;
      padding: 10px;
      
      
      
    }
</style>