<template>
  <van-tabbar v-model="active">
    <van-tabbar-item icon="fire" to="/">
        首页
   </van-tabbar-item>
   <van-tabbar-item icon="bars" to="/list">
        列表
    </van-tabbar-item>
    <van-tabbar-item icon="cart">购物车</van-tabbar-item>
    <van-tabbar-item icon="setting">我的</van-tabbar-item>
  </van-tabbar>

</template>
<script>
export default {
  data() {
    return {
      active: 0
    };
  }
};
</script>

