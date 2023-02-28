<template >
    <header>
        <div class="header">
            <div class="container">
                <div class="logo"><a href="#"> <div class="logo-img"></div></a></div>
                <div class="header-box">
                    <div class="settings">
                        <div class="moon item">
                            <img src="https://img.icons8.com/arcade/24/null/light.png"/>
                        </div>
                        <div class="sun item">
                            <img src="https://img.icons8.com/arcade/24/null/light-on.png"/>
                        </div>
                    </div>
                    <div class="language">
                        <select class="lang " aria-label=".form-select-lg example">
                            <option selected>Tilni Tanlang</option>
                            <option value="1">Uzb</option>
                            <option value="2">Rus</option>
                            <option value="3">Eng</option>
                        </select>
                    </div>
                    <div class="register-panel">
                        <div class="login reg"><a href="#">Login</a> </div>
                        <div class="sign-in reg"><a href="#">Register</a> </div>
                    </div>
                </div>
            </div>
        </div>
        
    </header>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    header{
        position: fixed;
        width: 100%;
        height: 80px;
        overflow: hidden;
        background: #9999998c;
        background: #bcc0c0;
        
        z-index: 1;
    }

    .container,.header-box{
        float: right;
        position: relative;
        height: 80px;
        display: flex;
        
    }
    header .header-box{
        width: 70%;
    }
    .logo{
        position: relative;
        width: 30%;
        text-align: center;
    }
    header .header-box{
        width: 70%;
        padding:0 190px;
    }
    header .header-box .settings .item{
        position: relative;
        width: 35px;
        height:35px;
        border-radius: 100px;
        text-align: center;
        cursor: pointer;
        margin:15px 0
    }
    header .header-box .settings .item:hover,.register-panel .reg:hover{
        background: #8888883d;
        transition: .5s ease all;
    }
    header .header-box .settings .sun{
        position: absolute;
    }
    .item img{
        padding:5px
    }
    
    .register-panel,.settings,.language{
        margin:auto 10px;
        
    }
    .register-panel{
        display: flex;
    }
    .register-panel .reg{
        margin:0 10px;
        padding: 5px 15px;
        border-radius: 100px;
    }
    .register-panel .reg a{
        color: #000;
    }
    
    .lang{
        background: none;
        border: none;
        outline: none;
    }
    .lang select option:hover{
        background: #000;
    }
    
    
</style>