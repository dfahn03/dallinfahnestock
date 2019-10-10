<template>
  <div class="title col-sm-12 d-flex justify-content-center align-items-center">

    <div class="row">
      <div class="col-12">
        <h1 class="job-title">Software Developer</h1>
      </div>
      <div class="col-12 mt-4">
        <h1 class="sJob-title">Full Stack Developer</h1>
      </div>
      <div class="col-12 mt-4">
        <h6 class="name">Dallin Fahnestock</h6>
      </div>
      <div class="col-12 mt-4">
        <button class="btn btn-lg contactBtn px-5" type="button" data-toggle="modal" data-target="#emailModal">Contact
          Me</button>
        <Email />
      </div>
      <div class="col-12 mt-4">
        <a href="https://www.linkedin.com/in/dfahnestock/"><img src="../assets/LinkedIn-70.png" title="LinkedIn"></a>
        <a href="https://github.com/dfahn03" class="ml-2"><img src="../assets/Github-70.png" class="githubBg"
            title="Github"></a>
        <a href="#emailModal" class="ml-2" data-toggle="modal"><img src="../assets/Email-70.png" title="Email"></a>
      </div>
    </div>

  </div>
</template>

<script>
  import Email from "@/components/Email.vue";

  export default {
    name: "Title",
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
  .title {
    color: white;
    text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;
  }

  .job-title {
    font-size: 63px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
  }

  .sJob-title {
    font-size: 45px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
  }

  .name {
    font-size: 30px;
    text-transform: uppercase;
    font-family: 'Monda', sans-serif;
  }

  .contactBtn {
    border: 2px solid white;
    border-radius: 10px;
    font-family: 'Monda', sans-serif;
    color: white;
    /* text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000; */
  }
</style>