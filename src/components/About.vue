<template lang="html">
    <div class="container animated fadeIn">
      <div class="row justify-content-center">
        <h2 class="animated fadeInUp">Just a simple Dude who's into exploring new stuff always!! 😎</h2>
        <ul style="margin-top:40px;">
          <li><h4 class="animated fadeInUp delay-1s">I'm a passionate Web developer</h4></li>
          <li><h4 class="animated fadeInUp delay-2s">Also a Gadget-holic</h4></li>
          <li style="margin-top:50px;"><h4 class="animated fadeInUp delay-3s">Languages I love to play with...</h4></li>
          <li>
            <div class="languages animated zoomIn delay-4s">
              <img src="https://img.icons8.com/color/48/000000/c-plus-plus-logo.png">
              <img src="https://img.icons8.com/color/48/000000/ruby-programming-language.png" alt="Ruby">
              <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python">
            </div>
          </li>
        </ul>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .container{
    margin-top: 100px;
  }
  ul{
    list-style-type: none;
    padding:0;
    margin:0;
  }
  body{
    text-color: black;
  }
  .languages img{
    padding: 15px;
  }
  @media screen and (max-width: 500px) {
    h2{
      font-size: 28px;
    }
    h4{
      font-size: 20px;
    }
  }
</style>
