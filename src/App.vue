<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <div className="container">
    <div className="header">
      <img src="/images/logo.png" className="logo" alt="logo" />
      <p>Welcome to the <span className="bold">Vue Js</span> starter project!</p>
    </div>
    <RouterView />
  </div>
</template>

<style scoped>
.container {
  position: relative;
  padding: 100px 15%;
}

.header {
  margin-bottom: 4rem;
}

.logo {
  width: 150px;
}
</style>