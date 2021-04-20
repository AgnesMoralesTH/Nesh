<template>
    <nav id="nav">
        <p class="logo">Natty</p>

        <ul class="nav-links">
            <li><router-link to="/" class="links">Home</router-link></li> 
    <li><router-link to="/shop" class="links">Shop</router-link></li>
    <li><router-link to="/" class="links">Contact</router-link> </li>
    <li><router-link to="/about" class="links">Info</router-link></li>
            
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
nav a.active{
    color: #42b983;
}
.nav-links{
    display: flex;
}
.links{
    padding-right: 20px;
    list-style: none;
}
.links:hover{
    text-decoration: underline;
}
</style>