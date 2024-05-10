<template>

  <div class="comp">

    <div class="left">
      <img src="../assets/logo.png">
      <h3 class="title">最专业的果农</h3>
      <p class="desc">他厌倦了生活。他们只和合适的孩子一起玩，他们和树林一起玩。</p>
    </div>

    <div class="right">
      <img src="../assets/logo.png">
      <h3 class="title">最棒的质量</h3>
      <p class="desc">他厌倦了生活。他们只和合适的孩子一起玩，他们和树林一起玩。</p>    
    </div>

  </div>

</template>


<style scoped>
.comp {
  display: flex;
  /* justify-content: space-between;  */
  justify-content: center; 
}

.comp .left .title {
color: black;
/* margin-left: 100px; */
/* width: 50%; */
}

.comp .right .title {
color: black; 
/* margin-right: 100px; */
/* width: 50%; */
}



.comp .left img{
  width: 10%;
  height: 55%;
  float: left;
  margin-left: 200px;
  margin-top: 10px;
}
.comp .right img {
  width: 10%;
  height: 55%;
  float: left;
  margin-left: 100px;
  /* margin-left: 400px; */
  margin-top: 10px;
}

.comp .left .title,
.comp .left .desc {
  margin-left: 300px; 
  text-align: left;
}

.comp .right .title,
.comp .right .desc {
  margin-left: 200px; 
  margin-right: 100px;
  text-align: left;
}

</style>