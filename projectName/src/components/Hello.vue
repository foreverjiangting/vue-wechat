<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <mt-button
        type="primary"
        @click="sheetVisible = true">
        测试Mint-UI
    </mt-button>
  </div>
</template>

<script>
import { Toast, MessageBox } from 'mint-ui';
export default {
  name: 'hello',
  data () {
    return {
      msg: '校招项目'
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
