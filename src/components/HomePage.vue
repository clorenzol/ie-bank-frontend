<template>
    <div>
      <h1>Welcome to My Website</h1>
      <p>This is the homepage of my website.</p>
    <div class="button-container">
      <router-link to="/skull" class="button">Skull</router-link>
      <router-link to="/accounts" class="button">Accounts</router-link>
    </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomePage',
  }
  </script>
  
  <style scoped>
  h1 {
    color: #333;
    font-size: 24px;
  }
  
  p {
    color: #666;
    font-size: 16px;
  }
  </style>
  