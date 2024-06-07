<template>
  <div class="navigation col-12 d-flex justify-content-center align-items-center">
    <div class="row">

      <!-- Small Navbar 
      <nav class="navbar fixed-top navbar-expand-sm" id="smNavbar">
        <a class="navbar-brand smBrand" href="#"><img src="../assets/D-2.gif" style="height: 50px;"
            class="d-logo"></a></a>
         Toggler/collapsibe Button
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <img src="../assets/Menu-Icon-40.png" title="Menu" class="menuImg">
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <div class="navbar-nav justify-content-center">
            <div class="row">
              <div class="col-11">
                <a href="#title" class="nav-item mr-3 mt-3">Home</a>
                <a href="#about" class="nav-item mr-3 mt-3">About</a>
                <a href="#skills" class="nav-item mr-3 mt-3">Skills</a>
                <a href="#experience" class="nav-item mr-3 mt-3">Experience</a>
                <a href="#projects" class="nav-item mr-3 mt-3">Projects</a>
              </div>
              <div class="col-1">              
                <button class="btn contactBtn px-5" type="button" data-toggle="modal" data-target="#emailModal">Contact Me</button>      
                <a href="#experience" class="nav-item mr-3 mt-3">Experience</a>
                <a href="#contact" class="nav-item mr-3 mt-3">Contact</a>
              </div>
            </div>
          </div>
        </div>
      </nav> -->

      <!-- Large Navbar -->
      <nav class="navbar fixed-top navbar-expand-sm" id="lgNavbar">
        <a class="navbar-brand smBrand" href="#"><img src="../assets/D-2.gif" style="height: 50px;"
            class="d-logo"></a>

        <!-- Toggler/collapsibe Button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <img src="../assets/Menu-Icon-40.png" title="Menu" class="menuImg">
        </button>

        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <div class="navbar-nav justify-content-center">
            <!-- <div class="col-11"> -->
              <a href="#title" class="nav-item">Home</a>
              <a href="#skills" class="nav-item">Skills</a>
              <a href="#experience" class="nav-item">Experience</a>
              <!-- <a class="navbar-brand lgBrand mb-0 mx-3"><img src="../assets/D-2.gif" style="height: 50px;" class="d-logo"></a> v-if="" -->
              <a href="#projects" class="nav-item">Projects</a>
              <a href="#about" class="nav-item">About</a>              
            <!-- </div> -->
            <!-- <div class="col-1"> -->
              <button class="btn contactBtn px-2" type="button" data-toggle="modal" data-target="#emailModal">Contact Me</button>
            <!-- </div> -->
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
    height: 6vh;
    /* text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000; */
  }

  /* .navItemAll {
    margin-right: 15px;
  } */

  .nav-item {
    /* justify-content: center; */
   margin-right: 17px;
   margin-top: 9px;
  }

  /* .navItemAbout {
    margin-right: 0px;
  } */

  /* .nav-itemHome {
    justify-content: center;
    margin-left: 4%;
  } */

  .navbar-toggler {
    border: 1px solid black;
  }

  .contactBtn {
    border: 2px solid white;
    border-radius: 10px;
    font-family: 'Monda', sans-serif;
    color: white;
    /* text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000; */
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
    font-weight:bolder;
  }

  .d-logo {
    border-radius: 15px;
  }
</style>