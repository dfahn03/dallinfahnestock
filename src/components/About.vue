<template>
  <div class="about col-12 d-flex justify-content-center align-items-center">

    <div class="row">
      <div class="col-12">
        <h1 class="aboutMe mb-5">About Dallin</h1>
      </div>

      <div class="col-lg-3 col-md-6 col-sm-12 d-flex justify-content-center mt-5">
        <div class="card text-white align-items-center" style="width: 25rem;">
          <img src="../assets/Boy-1.png" class="card-img-top" style="width: 9.5%;">
          <div class="card-body text-left">
            <p class="card-text">I started my love for technology when I was very young. Whether it was building a
              computer in 5th
              grade, playing video games, or helping family/friends with their technical issues.</p>
          </div>
        </div>
      </div>

      <div class="col-lg-3 col-md-6 col-sm-12 d-flex justify-content-center mt-5">
        <div class="card text-white align-items-center" style="width: 25rem;">
          <img src="../assets/Fit-2.gif" class="card-img-top" style="width: 21%">
          <div class="card-body text-left">
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

      <div class="col-lg-3 col-md-6 col-sm-12 d-flex justify-content-center mt-5">
        <div class="card text-white align-items-center" style="width: 25rem;">
          <img src="../assets/Pentester-2.png" class="card-img-top penTImg">
          <div class="card-body text-left">
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

      <div class="col-lg-3 col-md-6 col-sm-12 d-flex justify-content-center mt-5">
        <div class="card text-white align-items-center text-center" style="width: 25rem;">
          <img src="../assets/BoiseCodeWorks.png" class="card-img-top bcwImg">
          <div class="card-body text-left">
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
  }

  .job-title {
    font-size: 63px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
  }

  .card {
    background: transparent;
    border: none;
  }

  .fitImg,
  .penTImg,
  .bcwImg {
    width: 20%;
  }
</style>