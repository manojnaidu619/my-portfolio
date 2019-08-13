<template lang="html">
  <div>
    <h2 id="gfont">My Education</h2>
    <div class="container">
      <div class="row justify-content-center">
        <div class="card" style="width: 20rem;">
          <div class="card-body">
            <h5 class="card-title">Dayananda Sagar University</h5>
            <h6>Bangalore, India</h6>
            <h6>(2017-2021)</h6>
            <p class="card-text">Currently pursuing my Bachelors in Engineering with majors in Computer Science</p>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="card" style="width: 20rem;">
          <div class="card-body">
            <h5 class="card-title">Narayana PU College</h5>
            <h6>Bangalore, India</h6>
            <h6>(2015-2017)</h6>
            <p class="card-text">Graduated with 86.5% in class 12</p>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="card" style="width: 20rem;">
          <div class="card-body">
            <h5 class="card-title">Vidhatha Global High School</h5>
            <h6>Bangalore, India</h6>
            <h6>(2002-2015)</h6>
            <p class="card-text">Graduated with 89.6% in class 10</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  #gfont{
    font-family: 'Lobster', regular;
  }
  .card{
    background-color: Lightgray;
  }
  .row{
    margin-top: 20px;
  }
  body{
    text-color: black;
  }
</style>
