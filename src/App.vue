<template>
  <div id="nav">
  <h1>这里是肖恩嘻嘻的首页</h1>
    <div class="record">
      <a href="https://beian.miit.gov.cn" target="_blank">闽ICP备2021006317号</a>
      <div style="width:300px;margin:0 auto; padding:20px 0;">
        <a target="_blank" href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=35012102500342" style="display:inline-block;text-decoration:none;height:20px;line-height:20px;">
          <img src="https://lyu-oss.oss-cn-beijing.aliyuncs.com/img-bed/%E5%A4%87%E6%A1%88%E5%9B%BE%E6%A0%87.png" style="float:left;"/>
          <p style="float:left;height:20px;line-height:20px;margin: 0px 0px 0px 5px; color:#939393;">闽公网安备 35012102500342号
          </p>
        </a>
      </div>
    </div>
  </div>
  <router-view/>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  created () {
      console.log('这里是肖恩嘻嘻首页的控制台');
  },
  components: {
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
