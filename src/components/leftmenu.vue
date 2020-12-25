<template>
  <div class="leftmenu">
    <div class="leftmenu-top">
      <span class="leftmenu-top-span">Sean Wylie</span>
      <img src="@/assets/headimg.jpg" class="leftmenu-top-headimg" />
    </div>
    <div class="leftmenu-middle">
      <div class="leftmenu-middle-nav">
        <a href="https://blog.utone.xyz/" class="">
          首页
        </a>
        <a href="https://blog.utone.xyz/archives" class="">
          归档
        </a>
        <a href="https://blog.utone.xyz/categories" class="">
          分类
        </a>
        <a href="https://blog.utone.xyz/tags" class="">
          标签
        </a>
        <a href="https://blog.utone.xyz/friends" class="">
          友链
        </a>
        <a href="https://blog.utone.xyz/about" class="">
          关于
        </a>
      </div>
    </div>
  </div>
</template>

<style>
* {
  margin: 0 auto;
}
.leftmenu {
  float: left;
}
.leftmenu-top {
  padding-top: 20px;
}
.leftmenu-top-span {
  float: left;
  font-size: 26px;
  font-weight: bold;
  padding: 25px;
}
.leftmenu-top-headimg {
  display: inline-block;
  width: 60px;
  height: 60px;
  border-radius: 10px;
  margin: 10px;
}
.leftmenu-middle-nav {
  margin-top: 50px;
}
.leftmenu-middle-nav a {
  display: block;
  color: black;
  text-align: center;
  padding: 15px;
  font-size: 20px;
  text-decoration: none;
  font-weight: normal;
}
</style>
