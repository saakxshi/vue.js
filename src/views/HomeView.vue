<template>
  <div>
<h1>Lifecycle Hooks example</h1>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        counter: 0
      }
    },
    beforeCreate () {
      this.counter=1
      console.log("Before Create"+this.counter);;
    },
    created () {
      console.log("Created"+this.counter);;;
    },
  }
</script>

<style lang="scss" scoped>

</style>