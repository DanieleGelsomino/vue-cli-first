<template>
  <div class="Hero">
   <img src="https://i.stack.imgur.com/9E9Ud.png" alt="jumbotron">
   
  </div>
</template>

<script>
export default {
  name: 'HeroJumbo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
img{
  width: 100%;
  height: 450px;
}
</style>
