<template>

  <div class="title-content4">
    <img src="../assets/banner1.jpg">
    <div class="text">
      <span class="titlefirst-line">有机农作物滞销</span>
      <span class="titlesecond-line">救救我们！</span>  
      <p class="description">为了实现农业现代化，大力发展农业水平。</p>
      <button class="read-more-btn4">Read More</button>
      <!-- 添加圆形播放按钮 -->
      <button class="play-btn">
        <i class="iconfont icon-play"></i>
      </button>
    </div>
  </div>

</template>

<style scoped>
.title-content4 {
  position: relative;  
}

.title-content4 img {
  width: 100%;
  height: 300px;
  object-fit: fill;
}

 .text {
  /* position: relative;
  left: 300px; */
  position: absolute;
  top: 50px;
  color: rgb(255, 251, 251);
  font-size: 36px; 
  text-align: left; 
  margin-left: 200px;
}

.titlefirst-line {
  display: block; 
  font-weight: bold;
}

.titlesecond-line {
  display: block;
  margin-top: 5px; 
  font-size: 36px;
  font-weight: bold;
}


.description {
  margin-top: 10px; /* 注意这里应该是负值 */
  color: #ffffff;
  font-size: 14px;
} 
.read-more-btn4 {
  padding: 10px 15px;   
  margin-top: 10px; 
  background: transparent;
  color: #fff;
  border: solid;
  border-radius: 4px;
  cursor: pointer;
}
/* 为圆形播放按钮添加样式 */
.play-btn{
  position: absolute;
  bottom: 20px;
  right: -500px;
  cursor: pointer;
}
.play-btn i.iconfont{
  font-size:24px; /* 根据需要调整字体大小 */
}
.play-btn{
  display: inline-block; /* 将display属性设置为inline-block */
  width:60px; /* 根据需要调整宽度 */
  height:60px; /* 根据需要调整高度 */
  border-radius:50%; /* 将border-radius属性设置为50%以实现圆形 */
  background-color:#8d8a82; /* 根据需要调整背景颜色 */
}
</style>
