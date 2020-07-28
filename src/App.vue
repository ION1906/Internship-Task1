<template>
  <div id="app">
    <MyName name="Ilesanmi Oluwanifemi"/>
  </div>
</template>

<script>
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    MyName
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap" rel="stylesheet');

#app {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-family: 'Poppins', sans-serif;
  font-size: 22px;
  color: #000;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
