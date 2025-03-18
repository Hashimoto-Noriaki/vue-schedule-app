<template>
  <v-app>
    <v-container class="center">
      <h1 class="title">Hello Vuetify!</h1>
    </v-container>
  </v-app>
</template>

<script setup lang="ts">
</script>

<style scoped>
/* v-container を中央寄せ */
.center {
  display: flex;
  justify-content: center; /* 横方向の中央 */
  align-items: center; /* 縦方向の中央 */
  height: 100vh; /* 画面の高さ全体を使用 */
  color:limegreen;
}

.title {
  font-size: 24px;
  font-weight: bold;
  text-decoration: underline;
}
</style>
