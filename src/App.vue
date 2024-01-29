<template>
  <div class="parent-component">
    <SidePanel />
    <MainPanel />
  </div>
</template>

<script>
import SidePanel from "./layout/SidePanel.vue";
import MainPanel from "./layout/MainPanel.vue";

export default {
  name: "App",
  components: {
    SidePanel,
    MainPanel,
  },
};
</script>

<style scoped>
.parent-component {
  display: flex;
}
</style>
