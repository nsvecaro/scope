<template>
    <div class="layout-wrapper">
      <div class="nav-bar">
        <div class="logo">
          <img src="/icons/scope_white_logo.svg" alt="Scope Logo White" />
        </div>
  
        <ul class="nav-bar-links">
          <li>Usluge</li>
          <!-- <li>Billboards</li>-->
          <li>Blog</li>
          <li>O nama</li>
        </ul>
  
        <div class="cta">
          <Button>Javi se!</Button>
        </div>
      </div>

      <slot />


    </div>
  </template>
  
  <style scoped>
  .nav-bar {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    align-items: center;
    position: relative;
    margin: 40px 100px;
  }
  
  .logo {
    justify-self: start;
  }

  .logo img{
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
  

  </style>