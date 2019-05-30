<template>
  <footer>
    <ul>
      <router-link to="/" tag="li">
        <i class="iconfont icondianying1 ziti"></i>
        <p>电影</p>
      </router-link>
      <router-link to="/yingyuan" tag='li'>
        <i class="iconfont icondianying ziti"></i>
        <p>影院</p>
      </router-link>
      <router-link to="/wode" tag='li'>
        <i class="iconfont iconwebicon08 ziti"></i>
        <p>个人</p>
      </router-link>
    </ul>
  </footer>
</template>
<script>
export default {
  name: "footer1"
};
</script>
<style scoped>
footer {
    position: absolute;
    bottom: 0px;
    left: 0px;
  width: 100%;
  height: 50px;
  border-top: 1px solid #666;
}
ul{
    display: flex;
}
li{
    flex: 1;
    text-align: center;
    align-content: center;
}
.ziti{
    margin-top:10px;
    font-size: 20px;
}
</style>

