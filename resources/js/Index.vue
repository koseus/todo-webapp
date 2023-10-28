<template>
<div v-for="item in todoItems">


</div>
</template>

<script setup>
import ToDoItem from './Components/ToDoItem.vue'

defineProps(){
    todoItems: Array
}
</script>
