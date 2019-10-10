<template>
  <div class="email">

    <div class="modal fade" id="emailModal" tabindex="-1" role="dialog" aria-labelledby="emailModalLabel"
      aria-hidden="true">
      <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="emailModalLabel">Email</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <p>Coming Soon!</p>
            <p>Contact me with this email address:</p>
            <p class="emailAdd">dallin.jbs@gmail.com</p>
            <!-- <form @submit.prevent="">
              <div class="form-group">
                <label for="vaultInputName" class="col-form-label">Name:</label>
                <input type="text" v-model="newVault.name" class="form-control text-center" id="vaultInputName"
                  placeholder="Enter Vault Name" required>
              </div>
              <div class="form-group mb-4">
                <label for="vaultInputDescription" class="col-form-label">Description:</label>
                <input type="text" v-model="newVault.description" class="form-control text-center"
                  id="vaultInputDescription" placeholder="Enter Vault Description">
              </div>
              <button type="submit" class="btn btn-success">Create Vault</button>
            </form> -->
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
  }

  .emailAdd {
    color: blue;
  }
</style>