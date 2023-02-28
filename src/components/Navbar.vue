<template>
        <nav>
            <div class="nav-item">
                <i></i>
                <a href="#home">Asosiy</a>
            </div>
            <div class="nav-item">
                <i></i>
                <a href="#about">Haqida</a>
            </div>
            <div class="nav-item">
                <i></i>
                <a href="#images">Rasmlar</a>
            </div>
            <div class="nav-item">
                <i></i>
                <a href="#videos">Videolar</a>
            </div>
            <div class="nav-item">
                <i></i>
                <a href="#contact">Contact</a>
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
    height:50px;
    
    margin: 0px auto;
    text-align: center;
    border-bottom: 1px solid #8888881f;
    padding: 10px 5px;
    overflow: hidden;
}
.nav-item:hover{
    border-radius: 100px;
    background: #00000056;
    transition:all .5s ease
}

</style>