<template>
    <div class="home-page">
      <header class="header">
        <h1 class="box">
          <h2>Welcome to IE Bank Corporation</h2>
          <p>Make your Financial Dreams come True & Manage your Bank Accounts efficiently</p>
          <p> ______________________________________________________ </p>
          <p>Be part of the Future with our</p>
          <p>Digital Banking and Personalized Management</p>
        </h1>
  
        
        <h3>Select an option:</h3>
      
      </header>
    
      <div class="content">
        <router-link to="/accounts" class="button" active-class="active-button">Accounts</router-link>
        <router-link to="/skull" class="button" active-class="active-button">Skull</router-link>
      </div>
  
    </div>
  </template>
    
  <script>
    export default {
    }
  </script>
    
  <style scoped>
  .home-page {
    text-align: center;
    background-color: #30615dc9;
  }
  
  .header {
    background-image: url('../assets/images/4torres.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 80vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  
  .box {
    padding: 30px;
    background-color: #e2fbf8c3;
    margin-top: 150px;
  }
  
  h2 {
    font-family: Andale Mono;
    color: #000000;
    font-size: 55px;
  }
  
  p {
    font-family: Andale Mono;
    color: #040404;
    font-size: 16px;
    margin: 20px;
  }
  
  h3 {
    font-family: Andale Mono;
    background-color: #e2fbf8c3;
    color: #000000;
    font-size: 16px;
    padding: 10px 590px;
    margin-top: 100px;
  }
  
  .content {
    background-color: #e2fbf8c3;
  }
  
  .button{
    font-family: Andale Mono;
    display: inline-block;
    padding: 20px 40px;
    font-size: 18px;
    text-align: center;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    margin: 10px;
  }
  </style>
  