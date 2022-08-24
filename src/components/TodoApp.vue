<script setup>
import TodoForm from './TodoForm.vue';
import TodoList from './TodoList.vue';
</script>

<template>
    <div class="todo-app">
        <h1>Todo List with Pinia</h1>
        <todo-form />
        <todo-list />
    </div>
</template>

<style scoped>
.todo-app {
    width: 30vw;
    padding: 5vh;
    min-height: 100vh;
    background-color: #f7f9fc;
}
</style>