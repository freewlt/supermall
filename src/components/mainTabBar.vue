<template>
  <div class="mainTabBar">
    <tab-bar>
      <tabBarItem path="/home" activeColor="blue">
        <img slot="item-icon" src="@/assets/member.png">
        <img slot="item-icon-active" src="@/assets/memberSel.png">
        <div slot="item-text">首页</div>
      </tabBarItem>
      <tabBarItem path="/category" activeColor="blue">
        <img slot="item-icon" src="@/assets/member.png">
        <img slot="item-icon-active" src="@/assets/memberSel.png">
        <div slot="item-text">分类</div>
      </tabBarItem>
      <tabBarItem path="/cart" activeColor="blue">
        <img slot="item-icon" src="@/assets/member.png">
        <img slot="item-icon-active" src="@/assets/memberSel.png">
        <div slot="item-text">购物车</div>
      </tabBarItem>
      <tabBarItem path="/profile" activeColor="blue">
        <img slot="item-icon" src="@/assets/member.png">
        <img slot="item-icon-active" src="@/assets/memberSel.png">
        <div slot="item-text">我的</div>
      </tabBarItem>
    </tab-bar>
     <router-view/>
  </div>
</template>

<script>
import tabBar from '../components/tabbar/tabBar'
import tabBarItem from '../components/tabbar/tabBarItem'

export default {
  name: 'mainTabBar',
  components: {tabBar, tabBarItem},
  created () {
  }
}
</script>
