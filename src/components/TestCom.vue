<template>
  <div class="testcom">
    <h1>{{ tmsg }}</h1>
  </div>
</template>

<script>

export default {
  name: 'TestCom',
  data () {
    return {
      tmsg: 'this is a test component'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.test {
    background: #666;
}
</style>
