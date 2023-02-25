<script setup>
</script>

<template>
  <div class="layout1-container f-row f-center">
    <img class="layout1-image" src="../img/Image1.png" />
    <div class="layout1-content f48 f-dark-blue">HMT funds the processing of digitized work, and rewards workers for their contributions.</div>
  </div>
</template>

<style scoped>
    .layout1-container{
        padding: 193px 0px;
        width: 100%;
    }
    .layout1-image{
        width:100%;
        height:auto;
    }
    .layout1-content{
        width:608px;
    }
    @media (max-width: 1175px){
      .layout1-container{
        flex-direction: column!important;
      }      
    }
</style>
