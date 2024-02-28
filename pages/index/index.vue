<!--
 * @Description: index/index.vue   nuxt默认的首页
 * @Autor: zengbotao@myhexin.com
 * @Date: 2024-02-28 11:05:58
 * @LastEditors: Please set LastEditors
 * @LastEditTime: 2024-02-28 12:38:41
-->
<template>
  <div>
    <header>
      <h1>我的网站</h1>
      <a href="/">首页</a>
      <a href="/about">关于</a>
      <a href="/article">文章</a>
      <a href="/article/list">列表</a>
      <van-button type="primary">主要按钮</van-button>
      <van-button type="success">成功按钮</van-button>
      <van-button type="default">默认按钮</van-button>
      <van-button type="warning">警告按钮</van-button>
      <van-button type="danger">危险按钮</van-button>
    </header>
    <Nuxt />
  </div>
</template>
