<template>
  <div class="hello">
    <TestCom></TestCom>
    <h1>{{ msg }}</h1>
    
  </div>
</template>

<script>
import TestCom from '@/components/TestCom'
export default {
  name: 'HelloWorld',
  components: {
    TestCom
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
</style>
