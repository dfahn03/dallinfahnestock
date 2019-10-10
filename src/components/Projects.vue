<template>
  <div class="projects col d-flex justify-content-center align-items-center">
    <div class="row">
      <div class="col-12 mb-5">
        <h1 class="pTitle">Projects</h1>
      </div>
      <div class="col mt-5 d-flex justify-content-center">

        <a href="http://denotevator.herokuapp.com/#/login" class="custom-card">
          <div class="card text-white" style="width: 33rem;">
            <img src="../assets/kanban.gif" class="card-img" style="height: 18rem;">
            <div class="card-img-overlay">
              <h5 class="card-title">Kanban</h5>
            </div>
          </div>
        </a>

        <a href="http://kitchen-ninja1.herokuapp.com/#/login" class="custom-card">
          <div class="card ninjaCard pt-2 ml-2" style="width: 33rem; height: 18rem;">
            <img src="../assets/kninja.gif" class="card-img ninjaImg" style="width: 33%;">
            <div class="card-img-overlay">
              <h5 class="card-title">Kitchen Ninja</h5>
            </div>
          </div>
        </a>

        <a href="http://keeprdeploy3.herokuapp.com/#/" class="custom-card">
          <div class="card pt-0 ml-2" style="width: 33rem;">
            <img src="../assets/keep.gif" class="card-img" style="height: 18rem;">
            <div class="card-img-overlay">
              <h5 class="card-title">Keepr</h5>
            </div>
          </div>
        </a>



      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: "Projects",
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {}
  }
</script>

<style scoped>
  .pTitle {
    font-size: 50px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
  }

  .ninjaCard {
    /* background-color: #393e46; */
    background-image: url("https://media.istockphoto.com/photos/blurred-abstract-background-modern-kitchen-with-tabletop-and-space-picture-id935971392?k=6&m=935971392&s=612x612&w=0&h=BBpvZGyA1OU4kna2PhEKYAH86CpL127cHYkSpA-nE54=");
    /* background-image: url("https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fspecials-images.forbesimg.com%2Fdam%2Fimageserve%2F1129543819%2F960x0.jpg%3Ffit%3Dscale"); */
    /* background-image: url("https://i.pinimg.com/originals/9d/d7/6e/9dd76e2a489f893d51effabf2b8ec6f9.png"); */
    background-position: bottom;
    background-size: cover;
  }

  .card-title {
    color: black;
    /* color: #0092ca; */
    font-weight: 900;
    /* text-shadow: -1px -1px 0 #000, -1px -1px 0 #000, -1px 1px 0 #000, -1px 1px 0 #000; */

  }

  a {
    cursor: pointer;
  }

  .ninjaImg {
    margin-left: 35%;
    margin-top: 5%;
  }
</style>