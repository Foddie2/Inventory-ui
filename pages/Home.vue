<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <AppHeader/>
    <h2>Home component</h2>
    <p>table component should be here </p>
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";
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
    components: { AppHeader }
};
</script>

<style>

</style>
