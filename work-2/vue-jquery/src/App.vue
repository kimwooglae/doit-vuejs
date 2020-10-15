<template>
  <div id="app">
    App 컴포넌트
    <Picker></Picker>
  </div>
</template>

<script>

import Picker from './DatePicker.vue';

export default {
  created() {
    console.log($.fn.jquery);
    console.log($.ui.version);
  }, components: {
    Picker
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
