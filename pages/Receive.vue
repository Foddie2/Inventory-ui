<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <AppHeader/>
  <div class="container">
      <h1>Receive page component</h1>
  </div>

  </div>
</template>

<script>
  export default {
     head() {
      return {
        title: 'Receive',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Receive and process new inputs '

          }
        ]
      };
    }

  }
</script>

<style lang="scss" scoped>

</style>
