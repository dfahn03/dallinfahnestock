<template>
  <div class="projects col-12 d-flex justify-content-center">
    <div class="row">
      <div class="col-12">
        <h1 class="pTitle">Projects</h1>
      </div>

      <div class="col-lg col-md-12 col-sm-12">
        <a href="http://denotevator.herokuapp.com/#/login" class="custom-card">
          <div class="card kanbanCard text-white">
            <img src="../assets/kanban.gif" class="card-img kanbanImg">
            <div class="card-img-overlay">
              <h5 class="card-title kanbanTitle">Kanban</h5>
            </div>
          </div>
        </a>
      </div>
      <div class="col-lg col-md-12 col-sm-12">
        <a href="http://kitchen-ninja1.herokuapp.com/#/login" class="custom-card">
          <div class="card ninjaCard pt-2 ml-2">
            <img src="../assets/kninja.gif" class="card-img ninjaImg">
            <div class="card-img-overlay">
              <h5 class="card-title ninjaTitle">Kitchen Ninja</h5>
            </div>
          </div>
        </a>
      </div>

      <div class="col-lg col-md-12 col-sm-12">
        <a href="http://keeprdeploy3.herokuapp.com/#/" class="custom-card">
          <div class="card keepCard pt-0 ml-2">
            <img src="../assets/keep.gif" class="card-img keepImg">
            <div class="card-img-overlay">
              <h5 class="card-title keepTitle">Keepr</h5>
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

  a {
    display: inline-block;
    cursor: pointer;
  }

  .kanbanCard {
    width: 32.8rem;
  }

  .kanbanImg {
    height: 18rem;
  }

  .ninjaCard {
    width: 33rem;
    height: 18.2rem;
    background-image: url("https://us.123rf.com/450wm/urfingus/urfingus1606/urfingus160600006/58214688-professional-kitchen-facade-view-surface-in-stainless-steel-.jpg?ver=6");
    background-position: bottom;
    background-size: cover;
  }

  .ninjaImg {
    width: 33%;
    margin-left: 35%;
    margin-top: 5%;
  }

  .keepCard {
    width: 33rem;
  }

  .keepImg {
    height: 18rem;
  }

  .kanbanTitle {
    color: white;
    font-weight: 500;
    margin-top: 5px;
    /* text-shadow: -1px -1px 0 #000, -1px -1px 0 #000, -1px 1px 0 #000, -1px 1px 0 #000; */
  }

  .ninjaTitle {
    color: black;
    font-weight: 900;
    margin-top: 5px;
    /* text-shadow: -1px -1px 0 #000, -1px -1px 0 #000, -1px 1px 0 #000, -1px 1px 0 #000; */
  }

  .keepTitle {
    color: black;
    font-weight: 900;
    margin-top: 5px;
    /* text-shadow: -1px -1px 0 #000, -1px -1px 0 #000, -1px 1px 0 #000, -1px 1px 0 #000; */
  }

  @media screen and (max-width: 584px) {
    .pTitle {
      font-size: 35px;
      text-transform: uppercase;
      font-family: 'Monda', sans-serif;
      margin-top: 8vh;
    }

    .kanbanCard {
      width: 20rem;
    }

    .kanbanImg {
      height: 10rem;
    }

    .ninjaCard {
      width: 20rem;
      height: 10rem;
    }

    .ninjaImg {
      width: 30%;
      margin-left: 36%;
      margin-top: 5%;
    }

    .keepCard {
      width: 20rem;
    }

    .keepImg {
      height: 10rem;
    }
  }
</style>