<template>
    <nav id="nav">
        <p class="logo">Natty</p>

        <ul class="nav-links">
            <li><router-link to="/" class="links">Home</router-link></li> 
    <li><router-link to="/shop" class="links">Shop</router-link></li>
    <li><router-link to="/contact" class="links">Contact</router-link> </li>
    <li><router-link to="/Info" class="links">Info</router-link></li>
            
        </ul>

        
    </nav>
</template>

<style scoped>
#nav{
    display:flex;
    width: 500px;
    height: 100px;
     display: flex;
    justify-content: space-between;
    margin-top: 30px;
}
#nav a{
    font-weight: bold;
    color: black;
    text-decoration: none;
    
    
}

li:hover{
  color: grey;
}
.nav-links{
    display: flex;
}
.links{
    
    list-style: none;
}
li{
margin-right: 30px;
padding: 15px 5px 5px 5px;
height: 50px;
}
.logo{
  padding: 15px 5px 5px 5px;  
}
.links:hover{
    text-decoration: underline;
}
</style>