<template>
  <div class="container fluid">
    <div class="row justify-content-md-between">
      <div class="col">
        <router-link to="/" class="link">HOME</router-link>
      </div>
      <div class="col">
        <router-link to="/about" class="link">ABOUT</router-link>
      </div>
      <div class="col">
        <router-link to="/projects" class="link">PROJECTS</router-link>
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
  font-weight: bold;
  font-size: 17px;
  /*background: linear-gradient(to right,#B3FFAB, #12FFF7);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;*/
  color: Aqua;
}
.link:hover{
  text-decoration: none;
  border-bottom: 2px solid #FEE100;
}
.bread{
  display: none;
}
@media screen and (max-width: 500px) {
  /*.row{
    display: none;
  }*/
  .bread{
    display: block;
    float: right;
    margin-right: -10px;
  }
  .bread img{
    height: 30px;
    width: 30px;
    cursor: pointer;
  }
}
</style>
