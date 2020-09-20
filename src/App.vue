<template>
  <div id="app">
    <input
    
      v-model="message"
      type="text"

    />

      <h2 class="message">{{ message }}</h2>
      <router-view/>
  </div>  
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-size: 18px;
  font-family: 'Roboto', sans-serif;
  color: blue;
}
</style>