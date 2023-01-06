<script setup>
import Profile from '@/components/Profile.vue'


</script>

<template>
  <main>
    <div class="main-container">
      <Profile :key="$route.params.username"/>
    </div>
  </main>
</template>

<style scoped>
.main-container {
  padding: 0px 50px;
}
</style>