<template>
  <div id="app">
    <img src="./assets/logo.png"/>
    <Book-List></Book-List>
  </div>
</template>

<script>
import BookList from './components/BookList';

export default {
  name: 'app',
  components: {
   'Book-List': BookList
  },
};
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
</style>
