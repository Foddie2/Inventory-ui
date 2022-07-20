<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <section class="vh-100" style="background-color: #FCFAFA;">
  <div>
  <AppHeader/>
  <div class="container">
    <h2>Update page</h2>
  <div class="container py-5 ">
      <table class="table">
  <thead>
    <tr>
      <th scope="col">Stock ID</th>
      <th scope="col">Category Name</th>
      <th scope="col">Currency Quantity</th>
      <th scope="col">Unit cost</th>
      <th scope="col">Total Cost</th>
      <!-- <th scope="col">Btn</th> -->
      <th scope="col">Check All</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>MU003</td>
      <td>Mug</td>
      <td>1887</td>
      <td>Ksh 10,000</td>
      <td>Ksh 549</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
     <tr>
      <td>MU007</td>
      <td>Plate</td>
      <td>1768</td>
      <td>Ksh 9,000</td>
      <td>Ksh 949</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
     <tr>
      <td>MU004</td>
      <td>Tool kit</td>
      <td>1670</td>
      <td>Ksh 13,000</td>
      <td>Ksh 5578</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
     <tr>
      <td>MU008</td>
      <td>M</td>
      <td>1887</td>
      <td>Ksh 10,000</td>
      <td>Ksh 549</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
     <tr>
      <td>MU010</td>
      <td>Plate</td>
      <td>1800</td>
      <td>Ksh 900</td>
      <td>Ksh 1449</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
     <tr>
      <td>MU003</td>
      <td>Mug</td>
      <td>1887</td>
      <td>Ksh 10,000</td>
      <td>Ksh 549</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
     <tr>
      <td>MU003</td>
      <td>Mug</td>
      <td>1887</td>
      <td>Ksh 10,000</td>
      <td>Ksh 549</td>
      <th scope="row">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault" />
      </div>
      </th>
    </tr>
  </tbody>
</table>
  </div>
      </div>
  </div>
</section>

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
