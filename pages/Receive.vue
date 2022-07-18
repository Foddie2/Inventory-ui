<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <AppHeader/>
    <h1>Receive page component</h1>

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
