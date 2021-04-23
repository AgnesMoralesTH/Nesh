<template>
    <div class="main">
        <div class="banners">
            <div class="left">
                <h1 id="firstword">Hi, let's talk about your project!</h1>
                <img src="../assets/portrait.png" alt="" id="pook">
                <h3>Protip — touch on these things:

- Your idea
- Your timeline
- Your budget</h3>
            </div>

            <div id="right" class="contact">
                <section class="contact" id="contact">
                <div class="container">
				<h2>Contact</h2>
				
				<form>
					<div class="form-grid">
						<input type="text" name="name" id="name" placeholder="Name" class="form-element" />
						<input type="email" name="email" id="email" placeholder="Email" class="form-element" />
						<textarea name="message" id="message" placeholder="Messsage" class="form-area"></textarea>
					</div>
					<div class="right-align">
						<input type="submit" value="Send message" class="button" />
					</div>
				</form>
                </div>
                </section>
			</div>
        </div>


    </div>
</template>

<style scoped>
#firstword{
	background-color: rgb(black, 0.5);
}

h2 {
		text-align: center;
		margin-bottom: 32px;
		text-transform: uppercase;

		color: #313131;
		font-size: 36px;
	}
.button {
	appearance: none;
	border: none;
	outline: none;
	background: none;

	display: inline-block;
	color: #FFF;
	font-size: 20px;
	background-color: #FF9FDB;
	padding: 12px 16px;
	border-radius: 8px;
	text-decoration: none;
	text-transform: uppercase;
	font-weight: 700;
	cursor: pointer;

	@media (max-width: 767px) {
		font-size: 18px;
	}
}
.contact {
		background-color: #9B75D7;
        padding: 20px 20px 20px 20px;
		
}


.container {
			padding-top: 64px;
			padding-bottom: 64px;

			
			
        }

form {
				display: block;
				margin: 0 auto;
				max-width: 680px;

				

			}
            .form-grid {
					display: grid;
					grid-gap: 16px;
					grid-template-columns: repeat(2, 1fr);
					margin-bottom: 16px;
                    }
            @media (max-width: 767px) {
						grid-template-columns: 1fr;
					}

            .form-area {
						grid-column: 1/-1;
					}

				.right-align {
					text-align: right;
				}


.form-element, .form-area {
						appearance: none;
						border: none;
						outline: none;
						background: none;

						display: block;
						width: 100%;
						background-color: #FFF;
						border-radius: 8px;

						padding: 16px;
						font-size: 20px;
						color: #313131;

						
					}




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
#right{
    padding: 20px 20px 20px 20px;
  background-image: linear-gradient(to bottom left, rgb(255, 234, 237), rgb(245, 235, 236));
  height: 500px;
  width: 500px;
 
}
img{
    height: 300px;
    width: 300px;
}
.main{
    height: 100%;
 padding-top: 100px;
    background-image: linear-gradient(to bottom , rgb(232, 250, 255), rgb(255, 241, 224));
margin-top: -100px;
  
  width: 100%;
}
</style>