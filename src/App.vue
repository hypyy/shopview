<template>

  <div>
    <main-tab-bar></main-tab-bar>
    <router-view></router-view>
  </div>
</template>

<script>
  import MainTabBar from "./components/mainTabbar/MainTabBar";
export default {
  name: 'App',
  components:{
    MainTabBar
  }
}
</script>

<style>

</style>
