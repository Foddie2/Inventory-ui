<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
      <section class="vh-100" style="background-color: #FCFAFA;">

     <AppHeader/>
     <div class="container">
        <h1>Outbound page  Component</h1>

     </div>

</section>

  </div>
</template>

<script>
  export default {
     head() {
      return {
        title: 'Outbound',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Process management '

          }
        ]
      };
    }

  }
</script>

<style lang="scss" scoped>

</style>
