<!--
 * @Description: 不需要导入以及路由配置，只需要符合目录结构
 <NuxtPage/>相当于router-view
 * @Autor: zengbotao@myhexin.com
 * @Date: 2024-02-28 10:44:17
 * @LastEditors: Please set LastEditors
 * @LastEditTime: 2024-02-28 12:45:56
-->
<template>
  <div>
    <!-- 符合目录结构不必导入 -->
    <!-- <NuxtWelcome />  -->


    <NuxtPage/>
  </div>
</template>
<script setup lang="ts">
useSeoMeta({title:'zbt-web',description:'nuxt-learn'})
</script>
<style>
:root{
  /* 在这里全局修改vant按钮主题色 这里的style标签不能加上scoped，否则设置失败 */
  --van-button-primary-color:#FB7299;
}
</style>