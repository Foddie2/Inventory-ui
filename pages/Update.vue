<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
  <AppHeader/>
  <div class="container">
    <h2>Update page</h2>
      <table class="table">
  <thead>
    <tr>
      <!-- <th scope="col">
        <div class="form-check">
          <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
        </div>
      </th> -->
      <th scope="col">Stock ID</th>
      <th scope="col">Category Name</th>
      <th scope="col">Currency Quantity</th>
      <th scope="col">Unit cost</th>
      <th scope="col">Total Cost</th>
      <th scope="col">Btn</th>
      <th scope="col">Check All</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">
        <div class="form-check">
          <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
        </div>
      </th>
      <td>Sit</td>
      <td>Amet</td>
      <td>Consectetur</td>
    </tr>
    <tr>
      <th scope="row">
        <div class="form-check">
          <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
        </div>
      </th>
      <td>Adipisicing</td>
      <td>Elit</td>
      <td>Sint</td>
    </tr>
    <tr>
      <th scope="row">
        <div class="form-check">
          <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault"/>
        </div>
      </th>
      <td>Hic</td>
      <td>Fugiat</td>
      <td>Temporibus</td>
    </tr>
  </tbody>
</table>
  </div>



  </div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";
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
    },
    components: { AppHeader }

  };
</script>

<style lang="scss" scoped>

</style>
