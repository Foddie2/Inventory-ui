<template>
<div>
<nav class="navbar navbar-expand-lg navbar-light">
  <!-- Container wrapper -->
  <div class="container">
      <div class="container-fluid">
    <a class="navbar-brand">IMS</a>
    <div class="d-flex input-group w-auto">
      <NuxtLink to="/Home">
      <button type="button" class="btn btn-dark btn-rounded me-3 d-flex  mr-4">
        Menu
      </button>
      </NuxtLink>
      <NuxtLink to="/">
      <button type="button" class="btn btn-dark btn-rounded me-3 d-flex  mr-4">
        Home
      </button>
      </NuxtLink>
      <NuxtLink to="/">
      <button type="button" class="btn btn-dark btn-rounded me-3 d-flex  mr-4">
        Logout
      </button>
      </NuxtLink>
      <span class="input-group-text border-0">
        <i class="bi bi-person"></i>
      </span>
    </div>
  </div>
  </div>
  <!-- Container wrapper -->
</nav>
</div>
</template>
<script>
  export default {

  }
</script>

<style>

</style>
