<template>
    <footer>
      <h1 class = "titleA">Agrow<span style="color: #ffa200;">farm</span></h1>
      <div class="footer-content">
        <div class="left">
          <p>关于我们</p>
          <p style="color: #9a9894; font-size: small;">长城北大街东升街道星河596号</p>    
        </div>
        <div class="middleleft">
          <p>电话:</p>
          <p style="color: #ffa200;">400-888-8888</p>
          <p>邮箱:</p>  
          <p style="color: #ffa200;">hello@example.com</p>
        </div>
        <div class="middleright">
          <p>技术支持</p>
          <p style="color: #9a9894; font-size: small;">推特:@xxx </p>
          <p style="color: #9a9894; font-size: small;">联系我们</p>  
          <p style="color: #9a9894; font-size: small;">FAQ</p>  
        </div>
        <div class="right">
          <p>这里订阅</p>
          <div class="search-container">
            <input type="text" placeholder="邮件地址">
            <button>📨</button>
          </div>
          <p style="color: #9a9894; font-size: small;">订阅我们的邮件列表，并在您的电子邮件<br>
            收件箱中获取更新。</p>  
        </div>
      </div>
  
      <div class="copyright">
        Copyright @2023 Company Name All Rights Reserved.
      </div>
    </footer>
  </template>
  
  <style scoped>
  footer {
    background: #000;
    color: #fff;
    padding-top: 20px;
    padding-bottom: 50px;
    text-align: left;
  }
  .titleA{
    margin-left: 200px;
  }

  .footer-content {
    display: flex;
    justify-content: start; 
  }
  
  .footer-content .left {
    /* 排序在左 */
    margin-left: 200px;
  }
  .footer-content .middleleft{
    margin-left: 100px;
  }
  .footer-content .middleright{
    margin-left: 100px;
  }
  .footer-content .right {
    margin-left: 100px;
    margin-right: 100px;
    display: flex;
    flex-direction: column;
}
.right p {
  margin: 10px 0;
}
.right input[type="text"] {
  /* width: 200px;
  height: 30px;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 3px; */
  padding: 8px;
  border: none;
  border-radius: 2px;
}
.right button {
  padding: 7px 12px;
  background: #ffa200;
  color: #fff;
  border: none;
  border-radius: 2px;
}
.copyright {
  margin-top: 20px;
    text-align: center;
    font-size: smaller;
  }
  </style>
  