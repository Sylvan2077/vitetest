<template>  
    <div class="container">  
      <div class="left">  
        <img src="../assets/a6.jpg"  style="width: 300px;">  
      </div>  
      <div class="right">  
        <div class="title">我们种植健康的食物！</div>  
        <div class="paragraph">他厌倦了生活。他们把孩子们灌输给正确的人，超声波ligula. Semper at tempufddfel. Lorem ipsum dolor sit amet elit. Non
链接总是有一片雪花。他想痛苦。名称quae, fugiat nihil ad. Lorem ipsum dolor sit amet.
她不会逃跑的，她会受苦的。</div>  
        <div class="subtext-wrap">
          <div class="sub-textleft">有机解决方案</div>
          <div class="sub-textright">优质农业</div>  
        </div>
      </div>  
    </div>  
  </template>  
    
  <script>  
  import { ref } from 'vue';  
    
  export default {  
    name: 'MiddleComponent',  
    setup() {  
      const leftImage = ref(null);  
      return {  
        leftImage,  
      };  
    },  
  };  
  </script>  
    
  <style scoped>  
  .container {  
    display: flex;  
    justify-content: center;  
    align-items: center;  
    margin: 50px auto;
  }  
    
  .left {  
    /* margin-top: 50px; */
    margin-left: 200px;
    height: auto;
  }  
    
  .right {  
    flex-grow: 1;  
    display: flex;  
    flex-direction: column;  
    text-align: left;
    margin: auto 100px;

  }  
    
  .title {  
    position: relative;
    color: black;
    top: 0px; 
    font-size: 24px; /* 调整为实际的标题字号 */  
    margin-bottom: 50px; /* 调整为实际的标题与段落间距 */  
  }  
    
  .paragraph {  
    font-size: 10px; /* 调整为实际的段落字号 */  
    color: rgb(146, 146, 146);
  }  
    
  /* .sub-text {  
    display: inline-block; 
    vertical-align: middle;
    font-size: 12px; 
  }   */
  .subtext-wrap {
    margin-top: 30px;
    clear: both;
}
  .sub-textright{
  float: right;
  margin-right: 150px;
}
.sub-textleft {
  float: left; 
  margin-left: 0px;
}

  </style>