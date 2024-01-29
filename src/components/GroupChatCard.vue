<script></script>

<template>
  <div class="group-chat-card">
    <div>
      <img
        src="https://images.unsplash.com/flagged/photo-1570612861542-284f4c12e75f?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
        alt=""
      />
    </div>
    <div>
      <div class="first-section">
        <div>test</div>
        <div>Today, 13:40</div>
      </div>
      <div class="second-section">
        <div>bbbb</div>
        <div>arrow down</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.group-chat-card {
  display: flex;
}
.group-chat-card > div > img {
  width: 4rem;
  height: 4rem;
  border-radius: 50%;
}

.first-section,
.second-section {
  display: flex;
}
</style>
