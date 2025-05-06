<template>
    <h1 class="headline">
      <transition name="blur" mode="out-in">
        <span :key="currentText" class="changing-text">{{ currentText }}</span>
      </transition>
    </h1>
  </template>
  
  <script setup>
  import { ref, onMounted, onUnmounted } from 'vue'
  
  const phrases = [
    'u pravo vrijeme.',
    'na pravom mjestu.',
    'na pravoj platformi.',
    'pred pravom publikom.',
  ]
  
  const currentText = ref(phrases[0])
  let index = 0
  let intervalId
  
  onMounted(() => {
    intervalId = setInterval(() => {
      index = (index + 1) % phrases.length
      currentText.value = phrases[index]
    }, 4000)
  })
  
  onUnmounted(() => {
    clearInterval(intervalId)
  })
  </script>
  
  <style scoped>
  .changing-text {
    color: #B22222;
    position: relative;
  }
  
  .blur-enter-from,
  .blur-leave-to {
    opacity: 0;
    filter: blur(8px);
  }
  
  .blur-enter-active,
  .blur-leave-active {
    transition: all 0.6s ease;
  }
  
  .blur-enter-to,
  .blur-leave-from {
    opacity: 1;
    filter: blur(0px);
  }
  </style>