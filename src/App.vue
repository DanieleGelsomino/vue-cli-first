<template>
  <div id="app">
    <img alt="developer" src="https://miro.medium.com/max/1360/1*zVnWJtyGOX_kUIDm6ccCfQ.gif">
    <Title msg="La mia prima app con Vue CLI!"/>
    <Hero/>
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Hero,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
