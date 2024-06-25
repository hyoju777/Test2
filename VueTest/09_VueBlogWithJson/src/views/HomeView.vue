<script setup>
import TheWelcom from "@/components/home/TheWelcom.vue";
</script>

<template>
  <div class="home">
    <main>
      <TheWelcom />
    </main>
  </div>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 70%;
  margin-top: 1.5%;
  margin-left: auto;
  margin-right: auto;
  height: 90vh;
  background-color: white;
  padding: 13px;
  border: 1px solid black;
}
.home {
  background-color: black(255, 135, 135, 0.452);
}
</style>
