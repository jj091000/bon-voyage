<script>
export default {
  name: 'App',
}
</script>

<template>
  <div id="app">
    <img class="image" src="./assets/Bon-Voyage_Top.jpg" style="width: 100%;">
    <p class="center">Yèg cil</p>
    <p class="center">ak diam</p>
    <p class="center">Mane Sall </p>
  </div>

</template>

<style>
@import './styles/todomvc-base.css';
@import './styles/todomvc-index.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.center {
  margin: auto;
  padding: 10px;
  margin-top: 35px;
  color: cadetblue;
  font-size: 9vh;
}
</style>
