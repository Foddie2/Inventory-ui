<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
  <section class="vh-100" style="background-color: #FCFAFA;">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col col-xl-6">
        <div class="card" style="border-radius: 1rem;">
          <div class="row g-0">
              <div class="card-body p-4 p-lg-5 text-black">
                  <div class="pt-1 mb-1">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Update</button>
                  </div>
                    <div class="pt-4 mb-1">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Receive</button>
                  </div>
                    <div class="pt-4 mb-1">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Outbound</button>
                  </div>
                    <div class="pt-4 mb-1">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Reports</button>
                  </div>
              </div>
            </div>
          </div>
        </div>
    </div>
  </div>
</section>

  </div>
</template>

<script>
  export default {
     head() {
      return {
        title: 'Update',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Update and process new inputs '

          }
        ]
      };
    }

  }
</script>

<style lang="scss" scoped>

</style>
