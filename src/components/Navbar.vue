<template>
  <div class="container">
    <div class="row justify-content-md-between">
      <div class="col">
        <h5><router-link to="/" class="link"><img src="https://img.icons8.com/material-outlined/48/000000/home--v1.png" alt="Home"/></router-link></h5>
        <h6>Home</h6>
      </div>
      <div class="col">
        <h5><router-link to="/about" class="link"><img src="https://img.icons8.com/ios-filled/50/000000/education.png" alt="About"/></router-link></h5>
        <h6>About</h6>
      </div>
      <div class="col">
        <h5><router-link to="/projects" class="link"><img src="https://img.icons8.com/ios-filled/48/000000/programming.png" alt="Projects"/></router-link></h5>
        <h6>Projects</h6>
      </div>
    </div>
    <!--
    <div class="bread">
      <img src="https://img.icons8.com/ios-filled/50/000000/menu.png">
    </div> -->
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

 .link{
   color: white;
   text-decoration: none;
 }
 .col img{
   height: 40px;
   width: 40px;
 }
 .link img{
   transition: 0.1s linear;
 }
 .link img:hover{
   transform: scale(1.2);
 }

@media screen and (max-width: 500px) {
  .col img{
    height: 30px;
    width: 30px;
  }
  h6{
    display: none;
  }
  .container{
    margin-top: 20px;
  }
}
</style>
