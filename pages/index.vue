<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
  <section class="vh-100" style="background-color: #FCFAFA;">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col col-xl-10">
        <div class="card" style="border-radius: 1rem;">
          <div class="row g-0">
            <div class="col-md-6 col-lg-5 d-none d-md-block">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-login-form/img1.webp"
                alt="login form" class="img-fluid" style="border-radius: 1rem 0 0 1rem;" />
            </div>
            <div class="col-md-6 col-lg-7 d-flex align-items-center">
              <div class="card-body p-4 p-lg-5 text-black">
                <form action="bridge.php" method="post">
                  <div class="d-flex align-items-center mb-3 pb-1">
                    <i class="fas fa-cubes fa-2x me-3" style="color: #ff6219;"></i>
                    <span class="h1 fw-bold mb-0">IMS</span>
                  </div>
                  <h5 class="fw-normal mb-3 pb-3" style="letter-spacing: 1px;">Welcome back, Sign into your account and get started</h5>
                  <div class="form-outline mb-1">
                    <input type="email" id="form2Example17" class="form-control form-control-lg shadow-none" />
                    <label class="form-label" for="form2Example17">Name</label>
                  </div>
                  <div class="form-outline mb-1">
                    <input type="email" id="form2Example17" class="form-control form-control-lg shadow-none" />
                    <label class="form-label" for="form2Example17">Sales ID</label>
                  </div>
                  <div class="form-outline mb-1">
                    <input type="password" id="form2Example27" class="form-control form-control-lg shadow-none" />
                    <label class="form-label" for="form2Example27">Password</label>
                  </div>
                  <div class="pt-1 mb-1">
                    <NuxtLink to="/Home">
                    <button class="btn btn-dark btn-lg btn-block shadow-none" type="button">Login</button>
                    </NuxtLink>
                  </div>
                </form>
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
        title: 'Login',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Login and continue taking inventory '
          }
        ]
      };
    }

  }
</script>

<style >

</style>
