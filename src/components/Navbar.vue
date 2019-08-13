<template>
  <div>
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
</style>
