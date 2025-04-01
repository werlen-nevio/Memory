<template>
    <div class="app">
      <button @click="startGame">Start Game</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App',
    methods: {
      startGame() {
        console.log('Game started!');
        // Hier kannst du später deine Spiellogik starten
      }
    }
  }
  </script>
  
  <style scoped>
  .app {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f4f4f4;
  }
  
  button {
    padding: 10px 20px;
    font-size: 1.2rem;
    border: none;
    border-radius: 8px;
    background-color: #42b983;
    color: white;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  button:hover {
    background-color: #36966f;
  }
  </style>
  