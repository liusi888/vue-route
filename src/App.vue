<template>
  <div id="app">
      <!-- 使用 router-link 组件来导航. -->
      <!-- 通过传入 `to` 属性指定链接. -->
      <!-- <router-link> 默认会被渲染成一个 `<a>` 标签 -->
      <ul>
        <li><router-link to="/home">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
      <div>
       <!-- 路由匹配到的组件将渲染在这里 -->
         <router-view></router-view>
       </div>
  </div>
</template>

<script>


export default {
  components: {

  }
}
</script>

<style>

</style>
