<template>
  <div class="projects col-12 d-flex justify-content-center">
    <div class="row">
      <div class="col-12">
        <h1 class="pTitle">Projects</h1>
      </div>
      <div class="col-lg-12 d-flex justify-content-center">

        <a href="http://denotevator.herokuapp.com/#/login" class="custom-card">
          <div class="card text-white" style="width: 33rem;">
            <img src="../assets/kanban.gif" class="card-img" style="height: 18rem;">
            <div class="card-img-overlay">
              <h5 class="card-title">Kanban</h5>
            </div>
          </div>
        </a>

        <a href="http://kitchen-ninja1.herokuapp.com/#/login" class="custom-card">
          <div class="card ninjaCard pt-2 ml-2" style="width: 33rem; height: 18.2rem;">
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
    margin-top: 10vh;
  }

  .ninjaCard {
    /* background-color: #393e46; */
    background-image: url("https://us.123rf.com/450wm/urfingus/urfingus1606/urfingus160600006/58214688-professional-kitchen-facade-view-surface-in-stainless-steel-.jpg?ver=6");
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