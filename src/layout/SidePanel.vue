<script>
import Search from "../components/Search.vue";
import GroupChatCard from "../components/GroupChatCard.vue";

export default {
  name: "SidePanel",
  components: {
    Search,
    GroupChatCard,
  },
};
</script>

<template>
  <div class="border-solid border-2 border-yellow-600">
    <Search />
    <GroupChatCard />
  </div>
</template>

<style></style>
