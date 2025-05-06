<template>
  <div class="nav-bar">
  <div class="nav-content" :class="{ scrolled: isScrolled }">
    <div class="logo">
      <img src="/public/icons/scope_white_logo.svg" alt="Scope Logo White" />
    </div>

    <ul class="nav-bar-links">
      <li>Usluge</li>
      <!-- <li>Billboards</li> -->
      <li>Blog</li>
      <li>O nama</li>
    </ul>

    <div class="cta"  :class="{ scrolled: isScrolled}">
      <Button />
    </div>
  </div>
  </div>
</template>
<script setup>

import { ref, onMounted, onUnmounted } from 'vue'

const isScrolled = ref(false)

const handleScroll = () => {
  isScrolled.value = window.scrollY > 100
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>



<style scoped>
.nav-bar {
  position: sticky;
  top: 0;
  width: 100%;
  z-index: 100;
  display: flex;
  justify-content: center;
  background-color: transparent;
  font-size: 0.9rem;
}

.nav-content{
  display: grid;
  grid-template-columns: 1fr auto 1fr;
  align-items: center;
  width: 100%;
  margin: 10px 300px;
  padding: 10px 0;
  transition: all 0.5s ease-in-out;
  backdrop-filter: blur(0);
}

.nav-content.scrolled {
  display: grid;
  grid-template-columns: 1fr auto 1fr;
  align-items: center;
  width: 100%;
  margin: 10px 650px;
  padding: 5px;
  backdrop-filter: blur(10px);
  background-color: transparent;
  border-radius: 40px;
  border: 0.5px solid rgba(255, 255, 255, 0.345);
  line-height: 1;
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
}

.logo {
  justify-self: start;
  overlay: hidden;
}

.logo img {
  height: 25px;
}

.nav-bar-links {
  display: flex;
  gap: 30px;
  list-style: none;
  justify-content: center;
  padding: 0;
  margin: 0;
}

.cta {
  justify-self: end;
}

.cta Button {
  background-color: #e8e9e3;
  color: #202020;
  width: 200px;
  border: 1px solid transparent;
  font-weight: 500;
}

.cta Button:hover {
  background-color: rgba(255, 255, 255, 0);
  color: #e8e9e3;
  border: 1px solid #e8e9e3;
}

.cta.scrolled Button {
  background-color: #e8e9e3;
  color: #202020;
  width: 120px;
  border: 2px solid #e8e9e3;
  font-size: small;
  line-height: 1;
  padding: 8px;
  font-weight: 500;
}

.cta.scrolled Button:hover {
  background-color: rgba(255, 255, 255, 0);
  color: #e8e9e3;
  border: 1px solid #e8e9e3;
}


</style>