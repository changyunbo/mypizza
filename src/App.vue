<template>
  <div id="app" class="container">
    <!-- <img src="./assets/logo.png"> -->
    <Header></Header>
    <!-- 展示路由 -->
    <router-view/>
    <router-view name="history"></router-view>
    <!-- <router-view name="history"></router-view> -->

  </div>
</template>

<script>
import Header from '@/components/Header'
export default {
  name: 'App',
  data () {
    return {
      img:'../assets/logo.png' 
      
    }
  },
  components:{
    'Header':Header
  }
}
</script>

<style>

</style>
