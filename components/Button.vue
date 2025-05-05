<template>
    <button class="custom-button" @click="$emit('click')">
      Javi nam se!
    </button>
  </template>
  
  <style scoped>
  .custom-button {
    padding: 15px 30px;
    background-color: #B22222;
    color: #e8e9e3;
    border: 0px;
    border-radius: 30px;
    font-weight: 400;
    cursor: pointer;
    transition: all 0.3s ease;
    width: 150px;
    align-items: center;
    line-height: 1;
  }

  .custom-button:hover {
    background-color: #b2222298;
  }




  </style>