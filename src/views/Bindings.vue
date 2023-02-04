<template>
    <div class="home">
    <input type="text" v-model="user"> 
     <h1>Hello world {{user}}</h1>
  
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import HelloWorld from '@/components/HelloWorld.vue'
  
  export default {
    data() {
      return {
        user: 'Saakshi'
      }
    },
   
  }
  </script>
  
  
  
  
  
  
  
  
  