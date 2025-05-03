<template>
    <button class="custom-button" @click="$emit('click')">
      <slot />
    </button>
  </template>
  
  <style scoped>
  .custom-button {
    padding: 10px 15px;
    background-color: #B22222;
    color: #e8e9e3;
    border-radius: 10px;
    font-weight: 400;
    cursor: pointer;
    transition: all 0.3s ease;
  }
  
  .custom-button:hover {
    background-color: #861b1b;
    color: #e8e9e3;
  }
  </style>