<template>
  <div class="home container-fluid">
    <div class="row">
      <navigation />
    </div>
    <div class="row titleSection" id="title">
      <Title />
    </div>
    <div class="row aboutSection" id="about">
      <about />
    </div>
    <div class="row projectsSection" id="projects">
      <projects />
    </div>
    <div class="row skillSection" id="skills">
      <skills />
    </div>
    <div class="row expSection" id="exp">
      <experience />
    </div>


  </div>
</template>

<script>
  import Navigation from "@/components/Navigation.vue";
  import Title from "@/components/Title.vue";
  import About from "@/components/About.vue";
  import Projects from "@/components/Projects.vue";
  import Skills from "@/components/Skills.vue";
  import Experience from "@/components/Experience.vue";

  export default {
    name: 'home',
    components: {
      Navigation,
      Title,
      About,
      Projects,
      Skills,
      Experience
    }
  }
</script>

<style scoped>
  .home {
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .titleSection {
    /* background-image: url("../assets/bg-2.jpg"); */
    background-image: url("../assets/bg-4.jpg");
    height: 100vh;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .aboutSection,
  .projectsSection,
  .skillSection,
  .expSection {
    height: 92vh;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .aboutSection {
    /* background-image: url("../assets/bg-grey-1.jpg"); */
    background-color: #393e46;
  }

  .expSection,
  .projectsSection {
    background-color: #0092ca;
  }

  .skillSection {
    background-color: #393e46;
  }
</style>