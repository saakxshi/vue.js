<template>
    <div>
      <button @click="sayHello()" @mouseover="sayHello()">Click Me</button>
      <h1>You have pressed button {{ counter }} times</h1>
  
    </div>
  </template>
  
  <script>
    export default {
      data() {
        return {
          counter: 0
        }
      },
      methods: {
        sayHello() {
          console.log("hello from method");
          this.counter++;
        }
      },
    }
  </script>
  
  <style lang="scss" scoped>
  
  </style>