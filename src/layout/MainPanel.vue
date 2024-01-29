<script>
import MainPanelHeader from "../components/MainPanelHeader.vue";
import ChatPanel from "../components/ChatPanel.vue";

export default {
  name: "MainPanel",
  components: {
    MainPanelHeader,
    ChatPanel,
  },
};
</script>

<template>
  <div class="border-solid border-2 border-red-600">
    <MainPanelHeader />
    <ChatPanel />
  </div>
</template>

<style></style>
