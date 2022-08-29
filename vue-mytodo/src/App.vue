<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoTitle></TodoTitle>
    <TodoInput></TodoInput>
    <TodoContoroller></TodoContoroller>
    <TodoList></TodoList>
    <TodoFooter></TodoFooter>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TodoHeader from './components/TodoHeader.vue';
import TodoTitle from './components/TodoTitle.vue';
import TodoInput from './components/TodoInput.vue';
import TodoContoroller from './components/TodoContoroller.vue';
import TodoList from './components/TodoList.vue';
import TodoFooter from './components/TodoFooter.vue';

export default {
  name: 'App',
  components: {
    TodoHeader,
    TodoTitle,
    TodoInput,
    TodoContoroller,
    TodoList,
    TodoFooter
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
