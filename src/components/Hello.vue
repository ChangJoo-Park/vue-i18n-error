<template>
  <div class="hello">


   <p v-html="$t('message.hello')"></p>


    <el-button>Hello Yet Another Team Project</el-button>
  </div>
</template>

<script>
export default {
  name: 'hello',
  created () {
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
