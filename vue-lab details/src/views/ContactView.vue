<script setup lang="ts">
import UserCard from 'vue-lab details/src/components/UserCard.vue';
</script>

<template>
  <div class="contact-page">
    <h1>Сторінка контактів</h1>
    <p>Це наша нова сторінка контактів!</p>

    <UserCard username="Student_1" :isActive="true" />
    <UserCard username="Student_2" :isActive="1" /> <!--Помилка - написала 1 замість false-->

  </div>
</template>

<style scoped>
.contact-page {
  padding: 20px;
}
</style>
