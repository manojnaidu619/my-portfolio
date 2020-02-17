<template lang="html">
  <div id="text" class="animated fadeIn">
    <img class="animated fadeIn" src="/my-images/mj.jpg" alt="Manoj Naidu"/>
    <div class="description">
      <h1 class="animated slideInUp">Hi, I am Manoj Naidu</h1>
    </div>
    <div class="resume-div animated zoomIn">
      <a id="resume-btn" target="_blank" href="https://drive.google.com/file/d/1xepoKGa9Js7pQVloLtCCBlnea6BKwdte/view?usp=sharing">Resume</a>
    </div>
    <div class="social_links">
      <a href="https://github.com/manojnaidu619" target="_blank"><img class="animated fadeInLeft" id="github" src="/img/logos/github-home.png" alt="Github"></a>
      <a href="https://rubygems.org/profiles/manojnaidu619" target="_blank"><img id="rubygems" src="/img/logos/ruby.png" alt="Rubygems"></a>
      <a href="mailto:manojnaidu619@gmail.com?Subject=Hello!" target="_top"><img class="animated fadeInRight" id="email" src="/img/logos/gmail.png" alt="Gmail"></a>
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
 h1{
   color: black;
 }
 img{
   margin-top: 40px;
   width: 200px;
   height: 200px;
   border-radius: 125px;
 }
 .description{
   margin-top: 20px;
 }
 #github,#rubygems,#email{
   height:35px;
   width:35px;
   margin-right: 30px;
 }
 .resume-div{
   margin: 30px auto auto auto;
 }

 #resume-btn{
    width: 200px;
    padding: 8px;
    font-size: 16px;
    font-weight: 600;
    background-color: #393e46;
    border-radius: 5px;
    border: 1px solid #4c4c4c;
    color: floralwhite;
    text-transform: uppercase;
    letter-spacing: 2px;
    cursor: pointer;
    outline: none;
    text-decoration: none;
    display: inline-block;
    transition: 0.3s ease;
  }

  #resume-btn:hover{
    background-color: #393e46;
    letter-spacing: 4px;
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
   #github,#rubygems,#email{
     height:30px;
     width:30px;
     margin-right: 20px;
     margin-top: 30px;
   }
}
</style>
