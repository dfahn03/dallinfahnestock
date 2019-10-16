<template>
  <div class="skils col-12 d-flex justify-content-center">
    <div class="row justifty-content-center">
      <div class="col-12">
        <h1 class="mySkills">Skills</h1>
      </div>
      <!-- 
      <div class="col-12">
        <p class="otherSkills mt-3">JS Frameworks - Atlas DB - Dapper</p>
      </div> -->

      <div class="col-xl-12 col-lg-12 col-md-12 col-sm mb-1">
        <img src="../assets/html-js-css.png" class="w20">
        <img src="../assets/vue.png" class="w12">
        <img src="../assets/csharp.png" class="w7">
        <img src="../assets/node.png" class="w8 ml-3">
        <img src="../assets/netcore.png" class="w7 ml-3">
      </div>
      <div class="col-xl-12 col-lg-12 col-md-12 col-sm mb-2">
        <img src="../assets/api_rest.png" class="w15">
        <img src="../assets/api.png" class="w12">
        <img src="../assets/agile.png" class="w12">
        <img src="../assets/Boostrap_logo.svg" class="w7 ml-0">
        <img src="../assets/sql.png" class="w7 ml-3">
      </div>
      <div class="col-xl-12 col-lg-12 col-md-12 col-sm mb-5">
        <img src="../assets/vscode.png" class="w7 ml-3">
        <img src="../assets/docker.png" class="w10 ml-3">
        <img src="../assets/github.png" class="w9">
        <img src="../assets/mongodb.png" class="w7">
        <img src="../assets/gearhost.png" class="w7 ml-3">
      </div>


    </div>
  </div>
</template>

<script>
  export default {
    name: "Skils",
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {}
  }
</script>

<style scoped>
  .skills {
    font-family: 'Monda', sans-serif;
  }

  .mySkills {
    font-size: 50px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
    margin-top: 8vh;
  }

  @media screen and (min-width: 992px) {
    .w7 {
      width: 8%;
    }

    .w8 {
      width: 9%;
    }

    .w9 {
      width: 10%;
    }

    .w10 {
      width: 11%;
    }

    .w12 {
      width: 13%;
    }

    .w15 {
      width: 16%;
    }

    .w20 {
      width: 21%;
    }
  }

  @media screen and (height: 768px) {
    .w7 {
      width: 15%;
    }

    .w8 {
      width: 16%;
    }

    .w9 {
      width: 17%;
    }

    .w10 {
      width: 18%;
    }

    .w12 {
      width: 20%;
    }

    .w15 {
      width: 23%;
    }

    .w20 {
      width: 28%;
    }
  }

  @media screen and (min-width: 767px) and (max-width: 991px) {

    .w7 {
      width: 14%;
    }

    .w8 {
      width: 15%;
    }

    .w9 {
      width: 16%;
    }

    .w10 {
      width: 17%;
    }

    .w12 {
      width: 19%;
    }

    .w15 {
      width: 22%;
    }

    .w20 {
      width: 27%;
    }

    .otherSkills {
      font-size: 20px;
    }
  }

  @media screen and (max-width: 584px) {
    .mySkills {
      font-size: 35px;
      text-transform: uppercase;
      font-family: 'Monda', sans-serif;
      margin-top: 8vh;
    }

    .w7 {
      width: 12%;
    }

    .w8 {
      width: 13%;
    }

    .w9 {
      width: 14%;
    }

    .w10 {
      width: 15%;
    }

    .w12 {
      width: 17%;
    }

    .w15 {
      width: 20%;
    }

    .w20 {
      width: 25%;
    }
  }
</style>