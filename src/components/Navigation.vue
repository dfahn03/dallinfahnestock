<template>
  <div class="navigation col-12 d-flex justify-content-center align-items-center">
    <div class="row">


      <nav class="navbar fixed-top navbar-expand-sm">
        <a class="navbar-brand" href="#"><img src="../assets/D-2.gif" style="height: 50px;" class="d-logo"></a></a>

        <!-- Toggler/collapsibe Button -->
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <img src="../assets/Menu-Icon-40.png" title="Menu" class="menuImg">
        </button>

        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <div class="navbar-nav justify-content-center">
            <a href="" class="nav-item mr-3 mt-3">Home</a>
            <a href="" class="nav-item mr-3 mt-3">About</a>
            <a href="" class="nav-item mt-3">Projects</a>
            <a class="navbar-brand mb-0 mx-3" v-if=""><img src="../assets/D-2.gif" style="height: 50px;"
                class="d-logo"></a>
            <a href="" class="nav-item mr-3 mt-3">Skills</a>
            <a href="" class="nav-item mr-3 mt-3">Experience</a>
            <a href="" class="nav-item mr-3 mt-3">Contact</a>
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
    computed: {},
    methods: {},
    components: {}
  }
</script>

<style scoped>
  .navbar {
    background-color: rgba(255, 255, 255, 0.205);
    color: white;
    height: 8vh;
    /* text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000; */
  }

  .navbar-toggler {
    border: 1px solid black;
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