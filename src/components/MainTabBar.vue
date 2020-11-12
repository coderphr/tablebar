<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="deeppink">
        <img slot="item-icon" src="../assets/img/tabbar/tabbarhome.svg" alt />
        <img slot="item-icon-active" src="../assets/img/tabbar/tabbarhome-active.svg" alt />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="deeppink">
        <img slot="item-icon" src="../assets/img/tabbar/fenlei.svg" alt />
        <img slot="item-icon-active" src="../assets/img/tabbar/fenlei active.svg" alt />
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="deeppink">
        <img slot="item-icon" src="../assets/img/tabbar/gouwuche1 .svg" alt />
        <img slot="item-icon-active" src="../assets/img/tabbar/gouwuche1 active.svg" alt />
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="deeppink">
        <img slot="item-icon" src="../assets/img/tabbar/wode.svg" alt />
        <img slot="item-icon-active" src="../assets/img/tabbar/wode active.svg" alt />
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "./tabbar/TabBar";
import TabBarItem from "./tabbar/TabBarItem";

export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem
  }
};
</script>

<style>
</style>