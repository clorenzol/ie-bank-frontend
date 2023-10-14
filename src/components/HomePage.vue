<template>
  <div class="home-page">
    <h1>Welcome to IE Bank Corporation</h1>
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
.home-page {
  background-image: url('../assets/images/image-backround1.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

h1 {
  color: #fff;
  font-size: 32px;
  margin-bottom: 16px;
}

p {
  color: #fff;
  font-size: 16px;
  margin-bottom: 24px;
}

.buttons {
  display: flex;
  gap: 16px;
}

button {
  padding: 8px 16px;
  background-color: #fff;
  color: #333;
  border: none;
  border-radius: 4px;
  font-size: 14px;
  cursor: pointer;
}
</style>