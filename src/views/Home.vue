<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png"><br/>
    <button @click="handleClick">Endable Notifications</button><br/>
    <router-link to="/camera">
      Camera
    </router-link>
  </div>
</template>

<script>

export default {
  name: 'home',
  methods: {
    handleClick(){
      
    }
  }
}

</script>

<style scoped>

img {
  width: 30%;
}
</style>