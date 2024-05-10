<template>
  <div class="module">
    <h2 class="title">目前我们提供的</h2>

    <div class="img-wrap">
      <img src="../assets/a4.jpg" style="width: 200px;">
      <button class="floating-btn">农业先锋</button>
      <p>农业先锋会笑着来，没人想哭。</p>
    </div>
    <div class="img-wrap">
      <img src="../assets/a5.jpg" style="width: 200px;">  
      <button class="floating-btn">高质量保障</button>
      <p>高质量保障会笑，没人想哭。</p>      
    </div>
    <div class="img-wrap">
      <img src="../assets/a6.jpg" style="width: 200px;">
      <button class="floating-btn">有机服务</button>
      <p>有机服务让你笑着来，没人想哭。</p>
    </div>
  
  </div>
  </template>
  
  <style scoped>
  .module {
    position: relative;
    background-color: #f5f5f5; 
    text-align: center;
    padding-bottom: 50px;
  }  
  
  .title {
    color: black;
    padding-top: 50px;
    position: relative;
    font-size: 24px; 
    margin-bottom: 50px; 
  }
  
  .img-wrap {
    position: relative; 
    display: inline-block;
    text-align: center;
    width: calc(10% * 3); /* 将宽度设置为三张图片的总宽度 */
    height: auto;
    margin-right: 20px;
  }
  .img-wrap img {
  position: relative;
}

  .floating-btn {
    position: absolute;
  top: 120px;
  left: 150px; 
  z-index: 1;
  /* position: absolute; 
  top: 300px;
  left: auto; */
  /* top: 85%; 
  transform: translateY(-50%);  */
  padding: 9px 12px;
  background: #ffffff;
  color: #076c44;
  font-weight: bold;
  border: none;
  border-radius: 2px;
  cursor: pointer; /* 为鼠标悬停时添加指针样式 */
}
  .img-wrap p {
    margin-top: 20px; 
    font-size: small;
    color: #5b5a5a;
  }
  </style>