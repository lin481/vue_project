<template>
  <table border="1" width="500px" height="250px" cellspacing="0" cellpadding="0">
      <tr>
        <th align="center" colspan="3"><h2>PERSONAL CARD</h2></th>
        <th><img src="./assets/pic.jpg" alt="can't find" height="100"></th>
      </tr>


      <tr>
        <th>姓名：</th>
        <td>林嘉仪</td>
        <th>学号：</th>
        <td>2310274035</td>
      </tr>
      <tr>
        <th>邮箱：</th>
        <td>1584792785@qq.com</td>
        <th>手机：</th>
        <td>18124430354</td>
      </tr>
    
  </table>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
table{
  margin: auto;
  border-collapse: collapse;
}
</style>
