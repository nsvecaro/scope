<template>
    <Motion :variants="variants" appear>
      <slot />
    </Motion>
  </template>
  
  <script setup>
  const variants = {
    initial: { opacity: 0, y: 30 },
    visibleOnce: { opacity: 1, y: 0 },
    transition: { duration: 10, delay: 10, ease: 'easeOut' },
  }
  </script>