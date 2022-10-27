<template>
  <div id="app">
    <h1>
      Click Below to Access Team Sign-Up Form
    </h1>
    <button>
      <a 
        href="https://forms.gle/yP9vPjvE54VciRQe8"
        target="_blank"
        >
        Team Sign-Up Form
      </a>
    </button>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
body {
  background-color: black;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  color: white;
}

button {
  padding: 10px;
  border: 2px solid black;
  border-radius: 5px;
  background-color: white;
  cursor: pointer;
}

a {
  text-decoration: none;
  color: black;
  font-weight: bold;
  font-size: 2ch
}
</style>
