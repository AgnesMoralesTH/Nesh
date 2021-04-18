<template>
    <nav id="nav">
        <p class="logo">Natty</p>

        <ul class="nav-links">
            <li class="links">HOME</li>
            <li class="links">SHOP</li>
            <li class="links">CONTACT</li>
            <li class="links">INFO</li>
            
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