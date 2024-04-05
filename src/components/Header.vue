<template>
    <header>
      <h1>{{ title }}</h1>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/theWelcome">About</router-link></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    data() {
      return {
        title: ''
      };
    }
  };
  </script>
  
  <style scoped>
  </style>
  