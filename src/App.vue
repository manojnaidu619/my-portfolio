<template>
  <div class="container">

    <!-- Navbar -->
    <app-nav></app-nav>
    <!-- Navbar ends -->

    <div class="content container">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
 import Navbar from './components/Navbar'
 export default{
   components:{
     'app-nav': Navbar
   }
 }
</script>

<style>
  .container{
    text-align: center;
    margin-top: 25px;
  }
  .content{
    margin-top: 30px;
  }
</style>
