<template>
    <div>
      <button @click="add">{{count}}</button>
    </div>
  </template>
  
  <script setup>
  import { ref } from "vue";
  let count = ref(1)
  function add(){
      count.value++
  }
  </script>
  
  <style>
  button {
    color: red;
  }
  </style>