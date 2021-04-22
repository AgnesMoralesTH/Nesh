<template>
    <div class="main">
        <div class="banners">
            <div class="left">
                <h1>Hi, let's talk about your project!</h1>
                <img src="../assets/portrait.png" alt="" id="pook">
                <h3>Protip — touch on these things:

- Your idea
- Your timeline
- Your budget</h3>
            </div>

            <div class="right">
                <div class="container">
                    <h2>Contact</h2>

                    <form action="">
                        <div class="form-grid">
                            <input type="text" name="name" id="name" placeholder="name" class="form-element">
                            <input type="email" name="name" id="email" placeholder="email" class="form-element">
                            <textarea name="message" id="message" placeholder="Message" class="form-area"></textarea>
                        </div>

                    </form>
                </div>
            </div>
        </div>


    </div>
</template>

<style scoped>
.infoBox{
    height:100px;
    width: 200px;
    background-color: white;
}
.infoRow1{
    margin-top: 30px;
    display: flex;
    justify-content: space-between;
}
.banners{
 height: 550px;
        width: 1200px;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  
 


}
.left{
  
  width: 500px;
  height: 500px;
  padding-left: 0px;
}
.left h1{
  font-size: 50px;
  color: rgb(255, 255, 255);
}
.right{
    padding: 20px 20px 20px 20px;
  background-image: linear-gradient(to bottom left, rgb(255, 234, 237), rgb(229, 153, 165));
  height: 500px;
  width: 500px;
 border: 25px solid brown;
}
img{
    height: 300px;
    width: 300px;
}
.main{
    height: 100%;
 padding-top: 100px;
    background-image: linear-gradient(to bottom , rgb(62, 216, 255), rgb(91, 222, 255));
margin-top: -100px;
  
  width: 100%;
}
</style>