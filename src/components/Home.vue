<template lang="html">
  <div id="text">
    <img src="/my-images/manojnaidu.webp" alt="Manoj Naidu"/>
    <div class="description">
      <h1>Hi, I am Manoj Naidu</h1>
    </div>
    <div class="social_links">
      <a href="https://github.com/manojnaidu619" target="_blank"><img id="github" src="https://img.icons8.com/color/48/000000/github.png" alt="Github"></a>
      <a href="https://rubygems.org/profiles/manojnaidu619" target="_blank"><img id="rubygems" src="https://img.icons8.com/color/48/000000/ruby-programming-language.png" alt="Rubygems"></a>
      <a href="mailto:manonaidu619@gmail.com?Subject=Hello!" target="_top"><img id="email" src="https://img.icons8.com/color/48/000000/gmail.png" alt="Gmail"></a>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
 #text{
   color: white;
 }
 img{
   margin-top: 40px;
   width: 200px;
   height: 200px;
 }
 .description{
   margin-top: 20px;
 }
 #github,#rubygems,#email{
   height:40px;
   width:40px;
   margin-right: 30px;
 }

 @media screen and (max-width: 520px) {
   img{
     margin-top: 60px;
     width: 150px;
     height: 150px;
     /*margin-right: -35px;*/
   }
   h1{
     margin-top: 30px;
     font-size: 30px;
   }
   #facebook,#github,#rubygems,#email{
     height:30px;
     width:30px;
     margin-right: 20px;
     margin-top: 30px;
   }
}
</style>
