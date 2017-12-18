<template>
  <div id="app">
    <div class="banner-body">
     
      <keep-alive>
        <router-view></router-view>
      </keep-alive>
    
    </div>
  </div>
</template>

<script>
// 测试
export default {
  name: 'app'
}
</script>


