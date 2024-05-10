<template>
  <div class="title-content">
    <!-- 标题内容 --> 
  </div>
 
  <div class="content">
    <div class="left">
      <h2 class="subtitle">农作物&有机产品农场
        <br>形式
      </h2>
      <p class="text" style="top: 120px; left: 300px; font-size: 10%; color: rgb(123, 120, 120);">这对他来说会很痛苦，他会被认为是有帮助的，但他们会像生产和巨大的痛苦一样痛苦。因为当我走到最远的时候，谁会为我们工作？</p>  
      <p class="text" style="top: 170px;bottom: 0px; left: 300px;">新鲜蔬菜</p>  
      <p class="text" style="top: 195px;bottom: 0px; left: 300px;">产品</p>  
      <p class="text" style="top: 220px;bottom: 0px; left: 300px;">职业农民</p>
      <!-- <p class="text">第一行文字</p>
      <p class="text">第二行文字</p>  
      <p class="text">第三行文字</p>
      <p class="text">第四行文字</p> -->
    </div>
    <img class="big" src="../assets/a1.jpg">
    <div class="right">
      <img class="small top" src="../assets/a2.jpg">
      <img class="small bottom" src="../assets/a3.jpg">
    </div>
  </div>
 </template>
 
 <style scoped>
 .content {
   display: flex;
   background: #fff;
 }
 
 .left {
   flex: 1; 
   padding: 20px;
   position: relative;
   text-align: left;
 }
 
 .content .left .subtitle{
  position: absolute;
  left: 300px; 
  top: 30px;
 }
 .content .left .text{
  color: black;
  position: absolute;
  top: 100px; 
  /* padding-bottom: 10px;  */
  left: 300px; 
 }


 .content .right {
  /* padding-left: 200px; */
  display: flex;
  flex-wrap: wrap; 
}

.big {
  height: 300px;
  margin-left: 20px;
  /* margin-right: -200px;  */
}

.small {
  align-self: flex-start;
  width: 60%;
  height: 150px; 
  object-fit: scale-down;
}

.top {
  margin-bottom: 10px;
}
 </style>