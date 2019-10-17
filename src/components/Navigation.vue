<template>
  <div class="navigation col-12 d-flex justify-content-center align-items-center">
    <div class="row">

      <!-- Small Navbar -->
      <nav class="navbar fixed-top navbar-expand-sm" id="smNavbar">
        <a class="navbar-brand smBrand" href="#"><img src="../assets/D-2.gif" style="height: 50px;"
            class="d-logo"></a></a>
        <!-- Toggler/collapsibe Button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <img src="../assets/Menu-Icon-40.png" title="Menu" class="menuImg">
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <div class="navbar-nav justify-content-center">
            <div class="row">
              <div class="col-12">
                <a href="#title" class="nav-item mr-3 mt-3">Home</a>
                <a href="#about" class="nav-item mr-3 mt-3">About</a>
                <a href="#projects" class="nav-item mr-3 mt-3">Projects</a>
                <a href="#skills" class="nav-item mr-3 mt-3">Skills</a>
              </div>
              <div class="col-12">
                <!-- <a href="" class="nav-item mr-3 mt-3">Experience</a> -->
                <!-- <a href="#" class="nav-item mr-3 mt-3">Contact</a> -->
              </div>
            </div>
            <!-- TODO When a nav link is clicked, it will go to the section that you click on -->
          </div>
        </div>
      </nav>

      <!-- Large Navbar -->
      <nav class="navbar fixed-top navbar-expand-sm" id="lgNavbar">
        <a class="navbar-brand smBrand" href="#"><img src="../assets/D-2.gif" style="height: 50px;"
            class="d-logo"></a></a>

        <!-- Toggler/collapsibe Button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <img src="../assets/Menu-Icon-40.png" title="Menu" class="menuImg">
        </button>

        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <div class="navbar-nav">
            <a href="#title" class="nav-item mr-3 mt-3">Home</a>
            <a href="#about" class="nav-item mr-3 mt-3">About</a>
            <a class="navbar-brand lgBrand mb-0 mx-3" v-if=""><img src="../assets/D-2.gif" style="height: 50px;"
                class="d-logo"></a>
            <a href="#projects" class="nav-item mr-3 mt-3">Projects</a>
            <a href="#skills" class="nav-item mr-3 mt-3">Skills</a>
            <!-- <a href="" class="nav-item mr-3 mt-3">Experience</a> -->
            <!-- <a href="#" class="nav-item mr-3 mt-3">Contact</a> -->
            <!-- TODO When a nav link is clicked, it will go to the section that you click on -->
          </div>
        </div>
      </nav>

    </div>

  </div>
</template>

<script>
  export default {
    name: "Navigation",
    data() {
      return {}
    },
  }
</script>

<style scoped>
  .navbar {
    background-color: rgba(255, 255, 255, 0.205);
    color: white;
    height: 8vh;
    /* text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000; */
  }

  .navbar-nav {
    justify-content: center;
  }

  .navbar-toggler {
    border: 1px solid black;
  }

  @media screen and (height: 375px) {
    .navbar {
      height: 15vh;
    }
  }

  @media screen and (max-width: 575px) {

    .lgBrand,
    #lgNavbar {
      visibility: hidden;
    }

    .smBrand,
    #smNavbar {
      visibility: visible;
    }

    #smNavbar {
      background-color: rgb(255, 255, 255, 0.9);
      height: 8.4vh;
    }

    .nav-item {
      color: black;
      font-weight: 900;
    }

    .navbar-nav {
      background-color: rgba(255, 255, 255, 0.9);
      min-width: 90vw;
      display: flex;
      justify-content: start;
    }

    .menuImg {
      cursor: pointer;
    }
  }

  @media screen and (min-width: 576px) {

    .lgBrand,
    #lgNavbar {
      visibility: visible;
    }

    .smBrand,
    #smNavbar {
      visibility: hidden;
    }
  }

  a {
    color: white;
  }

  a:hover {
    color: blue;
    text-decoration: none;
  }

  .d-logo {
    border-radius: 15px;
  }
</style>