<script setup>
import AppHeaderInsurance from "./components/AppHeaderInsurance.vue";
import AppTheCompany from "./components/AppTheCompany.vue";
import AppExce from "./components/AppExce.vue";
import { ref } from "vue";

const m = ref([
  { title: "Home" },
  { title: "About" },
  { title: "Process" },
  { title: "service" },
  { title: "Team" },
  { title: "Blog" },
]);
</script>

<template>
  <div>
    <AppHeaderInsurance :menuItemsFromProp="m" />
    <AppTheCompany />
    <AppExce />
  </div>
</template>

<style lang="scss">
@use "./styles/general.scss";
</style>
