<template>
        <nav>
            <div class="nav-item">
                <i class="fas fa-heart"></i>
                <a href="#home">Asosiy</a>
            </div>
            <div class="nav-item">
                <i class="fa-solid fa-address-card"></i>
                <a href="#about">Haqida</a>
            </div>
            <div class="nav-item">
                <i class="fa-sharp fa-solid fa-image"></i>
                <a href="#images">Rasmlar</a>
            </div>
            <div class="nav-item">
                <i class="fa-solid fa-video"></i>
                <a href="#videos">Videolar</a>
            </div>
            <div class="nav-item">
                
                <a href="#contact" style="color:rgb(7, 177, 7)">Contact</a>
            </div>
        </nav>
</template>
<script>
export default {
    
}
</script>
<style scoped>

nav{
    position: fixed;
    width: 20%;
    height: 300px;
    background: #fff;
    
}
.nav-item{
    width:100%;
    height:60px;
    margin: 0px auto;
    border-bottom: 1px solid #8888881f;
    padding: 10px 5px;
    overflow: hidden;
    padding: 20px;
}
.nav-item:hover{
    border-radius: 100px;
    background: #00000056;
    transition:all .5s ease
}

i{
    
    margin-right:10px;
}

</style>