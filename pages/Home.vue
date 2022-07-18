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
                    <NuxtLink to="/Update">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Update</button>
                    </NuxtLink>
                  </div>
                    <div class="pt-4 mb-1">
                      <NuxtLink to="/Receive">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Receive</button>
                    </NuxtLink>
                  </div>
                    <div class="pt-4 mb-1">
                      <NuxtLink to="/Outbound">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Outbound</button>
                    </NuxtLink>
                  </div>
                    <div class="pt-4 mb-1">
                      <NuxtLink to="/Reports">
                    <button class="btn btn-dark btn-lg btn-block" type="button">Reports</button>
                     </NuxtLink>
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
            title: "Home",
            meta: [
                {
                    hid: "description",
                    name: "description",
                    content: "Manage your inventory with us "
                }
            ]
        };
    },

};
</script>

<style>

</style>
