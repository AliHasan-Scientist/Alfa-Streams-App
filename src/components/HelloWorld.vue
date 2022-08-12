
<!--our htm-->
<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Roy Ali Hasan</p>
  </div>
</template>
<!--our javascript-->
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p {
  background-color: #2c3e50;
  color: white;
  height: 50px;
  width: 110px;
  align-items: center;
}
</style>
