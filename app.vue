<!--
 * @Description: 不需要导入以及路由配置，只需要符合目录结构
 <NuxtPage/>相当于router-view
 * @Autor: zengbotao@myhexin.com
 * @Date: 2024-02-28 10:44:17
 * @LastEditors: Please set LastEditors
 * @LastEditTime: 2024-02-28 12:31:29
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