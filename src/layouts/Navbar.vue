<script setup>
    import HumanButtom from "../components/Button.vue"
    
</script>

<template>
  <div class="navbar-container">
        <img class="logo" alt="Vue logo" src="../img/HMark.png" />
        
        <div class="navbar-menu-container">
            <div class="navbar-menu f-row f-center">
                <div class="navbar-menu-item f16 f-dark-blue ftb"> Products </div>
                <div class="navbar-menu-item f16 f-dark-blue ftb"> Code </div>
                <div class="navbar-menu-item f16 f-dark-blue ftb"> Ecosystem </div>
                <div class="navbar-menu-item f16 f-dark-blue ftb"> Team </div>
                <div class="navbar-menu-item f16 f-dark-blue ftb"> Resources </div>
                <HumanButtom class="join-btn f-dark-blue f16 ftb" value="Join"/>
            </div>
        </div>
  </div>
</template>

<style scoped>
    .navbar-container{
        padding:62px 75px;
    }
    .logo{
        width:134.23px;
        height:32px;
        display: inline-block;
    }
    @media (max-width: 1175px) 
    {
           .navbar-menu-item{
                display: none!important;
           }
    }
    .navbar-menu-container{
        display: inline-block;
        float: right;
    }
    .navbar-menu-item {
        cursor:pointer;
        margin-left: 65px;
        
        background-color: none;
        transition: .2s;
    }
    .navbar-menu-item:hover{
        background-color: lightgray;
    }
    .join-btn{
        display: inline-block;
        float: right;
        width:144px;
        height:56px;
        margin-left: 68px;
    }
</style>
