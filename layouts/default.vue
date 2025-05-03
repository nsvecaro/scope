<template>
    <div class="layout-wrapper">
      <div class="nav-bar">
        <div class="logo">
          <img src="/icons/scope_white_logo.svg" alt="Scope Logo White" />
        </div>
  
        <ul class="nav-bar-links">
          <li>USLUGE</li>
          <li>BILLBOARDS</li>
          <li>O NAMA</li>
          <li>BLOG</li>
        </ul>
  
        <div class="cta">
          <Button>Kontaktiraj nas</Button>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .layout-wrapper {
    margin: 40px 100px;
  }
  
  .nav-bar {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    align-items: center;
    position: relative;
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