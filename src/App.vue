<template>
  <div id="app">
    
    <Title/>
    
  </div>
</template>

<script>

import Title from './components/Title.vue';
export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style lang="scss">
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  background-image: url(https://media.wsimag.com/attachments/63407be7cde1b5c9bbeca37fb767c6311411fac9/store/fill/860/645/dcd07dd586650510caaa8758a7a609c21efe932fc87c47bd31df00ad604d/Cybersecurity.jpg);
  width: 100%;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
