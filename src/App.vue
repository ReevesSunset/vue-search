<template>
  <div id="app">
    <input type="text" placeholder="搜索(汉字,首字母,拼音)">
    <ul>
      <li v-for="item in dataList">{{item}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      data: 'dasda',
      dataList: ['zd', 'xs']
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

li {
  list-style: none;
}

input {
  width: 200px;
  height: 40px;
}
</style>
