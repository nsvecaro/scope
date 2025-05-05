<template>
      <div class="nav-bar">
        <div class="logo">
          <img src="/public/icons/scope_white_logo.svg" alt="Scope Logo White" />
        </div>
  
        <ul class="nav-bar-links">
          <li>Usluge</li>
          <!-- <li>Billboards</li>-->
          <li>Blog</li>
          <li>O nama</li>
        </ul>
  
        <div class="cta">
          <Button />
        </div>
      </div>
  </template>
  
  <style scoped>
  .nav-bar {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    align-items: center;
    position: relat;
    margin: 20px 100px;
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

  .cta Button{
    background-color: #e8e9e3;
    color: #202020;
    width: 200px;
    border: 1px solid transparent;

  }

.cta Button:hover{
    background-color: rgba(255, 255, 255, 0);
    color: #e8e9e3;
    border: 1px solid #e8e9e3;
    
  }
  
  </style>