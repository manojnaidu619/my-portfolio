<template lang="html">
  <div>
    <h2 id="gfont">About my Education</h2>
    <div class="container">
      <div class="row justify-content-center">
        <div class="card" style="width: 25rem;">
          <div class="card-body">
            <img src="/my-images/UG.png" alt="Dayananda Sagar University">
            <h3 class="card-title">Dayananda Sagar University</h3>
            <h5>Bangalore, India</h5>
            <h6>(2017-2021)</h6>
            <p class="card-text">Currently pursuing my Bachelors in Engineering with majors in Computer Science</p>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="last card" style="width: 25rem;">
          <div class="card-body">
            <img id="ug" src="/my-images/college.jpg" alt="Narayana PU college">
            <h3 class="card-title">Narayana PU College</h3>
            <h5>Bangalore, India</h5>
            <h6>(2015-2017)</h6>
            <p class="card-text">Graduated with 86.5% in class 12</p>
          </div>
        </div>
      </div>

      <!-- <div class="row justify-content-center">
        <div class="last card" style="width: 25rem;">
          <div class="card-body">
            <img src="school.png" alt="Vidhatha Global school">
            <h3 class="card-title">Vidhatha Global High School</h3>
            <h5>Bangalore, India</h5>
            <h6>(2002-2015)</h6>
            <p class="card-text">Graduated with 89.6% in class 10</p>
          </div>
        </div>
      </div> -->

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  #ug{
    border-radius: 25px;
  }
  #gfont{
    font-family: 'Lobster', regular;
  }
  .card{
    background-color: Lavender;
  }
  .row{
    margin-top: 20px;
  }
  body{
    text-color: black;
  }
  img{
    height: 80px;
    width: 80px;
    margin-bottom: 10px;
  }
  .last{
    margin-bottom: 50px;
  }
  @media screen and (max-width: 500px) {
    img{
      height: 60px;
      width: 60px;
    }
    h3{
      font-size: 22px;
    }
    h5{
      font-size: 16px;
    }
  }
</style>
