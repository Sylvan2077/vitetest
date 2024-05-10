<template>

    <div class="comp">
      <img class="bg" src="../assets/banner4.jpg">
      <h2 class="title">瓜果滞销 救救我们</h2>
      <p class="text">
        他想痛苦。他希望，如果他想像他一样，为了时间的痛苦，他会乐意赞扬任何事情。多洛雷斯骚扰的开心果很抱歉！。他会被认为是乐于助人的。他们是他们选择的建筑师。
      </p>
      <!-- 在.text下面添加一个圆形头像图片 -->
      <img class="avatar" src="../assets/logo.png" alt="Avatar" style="width: 3%;">
      <!-- 在头像右边添加文字说明 -->
      <p class="text-description">John Wilson</p>
    </div>
  
  </template>
  
  
  <style scoped>
  .comp {
    position: relative;
    /* padding: 50px 0; */
  }
  
  .bg {
    width: 100% ;
    height: 400px;
    object-fit: cover;
  }  
  
  .title {
    position: absolute;
    top: 50px;
    left: 50%;
    transform: translateX(-50%); 
    /* 将元素沿着横向（x轴）移动自身宽度的50%，也就是说，元素将从左侧0点向左移动自身宽度的50% */
    color: #fff;
    font-size: 36px;
  }
  
  .comp .text {
    position: absolute;
    color: #fff;
    text-align: center;
    left: 50%;
    top: 200px;
    transform: translateX(-50%); 
    font-weight: bold;

  }
  /* 为圆形头像添加样式 */
  .avatar {
  position: absolute;
  top: 300px;
  left: 45%;
  transform: translateX(-50%); 
  border-radius: 50%; /* 使图片呈现圆形 */
  margin-right: 20px; /* 为了给文字说明留出空间 */

  }
  .text-description{
    color: #fff;
    position: absolute;
    top: 290px;
    left: 650px;
    transform: translateX(-50%); 
    font-weight: bold;

  }
  </style>
  