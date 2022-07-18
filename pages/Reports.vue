<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <AppHeader/>
  <div class="container">
      <h1>Get your reports here</h1>
  </div>

  </div>
</template>

<script>
  export default {
     head() {
      return {
        title: 'Reports',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Get reports on process and new inputs '

          }
        ]
      };
    }

  }
</script>

<style lang="scss" scoped>

</style>
