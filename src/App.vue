<template>
  <div id="app">
            <div class="container-fluid">
            </div>
      <api-component></api-component>

  </div>
</template>

<script>
import ApiComponent from "./components/ApiComponent.vue";

export default {
  name: "App",
  components: {
    ApiComponent,
  },
};
</script>

