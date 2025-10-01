<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="greetings">
    <h1 class="message">{{ msg }}</h1>
  </div>
</template>

<style scoped>
h1 {
  text-decoration: none;
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
}

.greetings h1 {
  text-align: center;
  display: flex;
  justify-content: center;
}
</style>
