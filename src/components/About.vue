<template>
  <div class="about col-12 d-flex justify-content-center">

    <div class="row">
      <div class="col-12">
        <h1 class="aboutMe">About Dallin</h1>
      </div>

      <div class="col-xl col-lg-6 col-md col-sm-12 d-flex justify-content-center">
        <div class="card text-white align-items-center">
          <img src="../assets/Boy-1.png" class="card-img-top" style="width: 9.5%;">
          <div class="card-body text-center">
            <p class="card-text">My love for technology started at a very young. Whether it was building a
              computer in 5th
              grade, playing video games, or helping family/friends with their technical issues.</p>
          </div>
        </div>
      </div>

      <div class="col-xl col-lg-6 col-md col-sm-12 d-flex justify-content-center">
        <div class="card text-white align-items-center">
          <img src="../assets/Fit-2.gif" class="card-img-top" style="width: 21%">
          <div class="card-body text-center">
            <p class="card-text">I began working in the fitness industry,
              which I
              loved for numerous reasons, one of which being the built-in need for continuing education. I found
              that I
              enjoyed the
              constant learning and improving myself. That has served me well as I moved back into the
              technical industry
              where I began.</p>
          </div>
        </div>
      </div>

      <div class="col-xl col-lg-6 col-md col-sm-12 d-flex justify-content-center">
        <div class="card text-white align-items-center">
          <img src="../assets/Pentester-2.png" class="card-img-top penTImg">
          <div class="card-body text-center">
            <p class="card-text">In 2017, I was approached by a former NSA programmer and penetration tester for an
              opportunity to start
              my professional career in the industry, and I immediately began to train with him as I wanted to
              return to
              technology. I
              was actively mentored by him for six months, and spent 10-12 hours a day studying because I enjoyed it
              so
              much. Since
              finishing that training, I have been seeking out additional avenues to grow in my skill set.</p>
          </div>
        </div>
      </div>

      <div class="col-xl col-lg-6 col-md col-sm-12 d-flex justify-content-center">
        <div class="card text-white align-items-center text-center">
          <img src="../assets/BoiseCodeWorks.png" class="card-img-top bcwImg">
          <div class="card-body text-center">
            <p class="card-text">I
              discovered BoiseCodeWorks in my search for growth, an immersive Full Stack Developer training program
              that is based in Idaho.
              I
              moved from Utah
              and started the course within a week, as I was and continue to be dedicated to growing in this field.
              I
              completed their
              course and found that, like my previous experiences in technical fields, it was very challenging but
              also
              incredibly
              fun. It takes hard work, studying and practice which I bring from my past experience. I thrive on the
              creativity of
              development, the ability to build something out of nothing, and the constant need to grow and improve
              myself
              to be
              skilled at this field.</p>
          </div>
        </div>
      </div>

    </div>
  </div>

  </div>
</template>

<script>
  import Email from "@/components/Email.vue";

  export default {
    name: "About",
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {
      Email
    }
  }
</script>

<style scoped>
  .about {
    color: white;
    /* color: #1998ff; */
  }

  .aboutMe {
    font-size: 50px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
    margin-top: 10vh;
  }

  .card {
    background: transparent;
    border: none;
    width: 20rem;
  }

  .fitImg,
  .penTImg,
  .bcwImg {
    width: 20%;
  }

  .card-img-top {
    margin-bottom: 2%;
  }


  @media screen and (max-width: 767px) {
    .aboutMe {
      font-size: 35px;
      text-transform: uppercase;
      font-family: 'Monda', sans-serif;
      margin-top: 8vh;
    }

    .card-body {
      margin-bottom: 0;
      padding-bottom: 0;
    }

    .card-text {
      font-size: 15px;
    }
  }

  @media screen and (min-width: 1530px) {
    .card {
      width: 24rem;
    }

    .card-text {
      font-size: 18px;
    }
  }
</style>