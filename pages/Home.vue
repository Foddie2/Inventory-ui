<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <!-- Container wrapper -->
  <div class="container">
      <div class="container-fluid">
    <a class="navbar-brand">IMS</a>


    <form class="d-flex input-group w-auto">

      <button type="button" class="btn btn-primary me-3 d-flex ">
          Refresh
        </button>
         <button type="button" class="btn btn-primary me-3 d-flex">
          Logout
        </button>
      <span class="input-group-text border-0" id="search-addon">
        <i class="fas fa-search"></i>
      </span>
    </form>
  </div>
  </div>
  <!-- Container wrapper -->
</nav>
<!-- Navbar -->


  </div>
</template>

<script>
  export default {
    head() {
      return {
        title: 'Home',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Manage your inventory with us '

          }
        ]
      };
    }

  };
</script>

<style>

</style>
