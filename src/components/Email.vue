<template>
  <div class="email col">

    <div class="modal fade" id="emailModal" tabindex="-1" role="dialog" aria-labelledby="emailModalLabel"
      aria-hidden="true">
      <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title ml-2" id="emailModalLabel">Email</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true" class="mr-2">&times;</span>
            </button>
          </div>
          <div class="modal-body mt-3">
            <!-- <p>Coming Soon!</p> -->
            <p>Contact me @: dallin.jbs@gmail.com</p>
            <!-- <p class="emailAdd mb-4">dallin.jbs@gmail.com</p> -->
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: "Email",
    data() {
      return {}
    },
    computed: {},
    methods: {},
    components: {}
  }
</script>

<style scoped>
  .email {
    color: black;
    text-shadow: none;
    font-weight: 600;
  }

  .modal-dialog {
    left: 35%;
  }

  .emailAdd {
    color: blue;
  }

  @media screen and (max-width: 584px) {
    .modal-dialog {
      left: 0%;
    }
  }

  @media screen and (height: 375px) {
    .modal-dialog {
      left: 20%;
      top: 10%;
    }
  }

  @media screen and (width: 768px) {
    .modal-dialog {
      left: 20%;
    }
  }

  @media screen and (width: 1024px) {
    .modal-dialog {
      left: 25%;
    }
  }
</style>