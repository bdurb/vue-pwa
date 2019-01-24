<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png"><br/>
    <button @click="handleClick">Endable Notifications</button>
  </div>
</template>

<script>

export default {
  name: 'home',
  methods: {
    handleClick(){
      console.log('hello')
    }
  }
}

</script>

<style scoped>

img {
  width: 30%;
}
</style>