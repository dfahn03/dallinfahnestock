<template>
  <div class="navigation container-fluid">

    <nav class="navbar fixed-top navbar-expand-lg">
      <div class="collapse navbar-collapse justify-content-center">
        <div class="navbar-nav">
          <a href="" class="nav-item mr-3 mt-3">Home</a>
          <a href="" class="nav-item mr-3 mt-3">About</a>
          <a href="" class="nav-item mt-3">Projects</a>
          <a class="navbar-brand mb-0 mx-3"><img src="../assets/D-2.gif" style="height: 50px;" class="d-logo"></a>
          <a href="" class="nav-item mr-3 mt-3">Skills</a>
          <a href="" class="nav-item mr-3 mt-3">Experience</a>
          <a href="" class="nav-item mr-3 mt-3">Contact</a>
          <!-- TODO When a nav link is clicked, it will go to the section that you click on -->
        </div>
      </div>
    </nav>

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