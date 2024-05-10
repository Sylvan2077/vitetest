<template>

  <div class="title-content">
    <img src="../assets/banner1.jpg">
    <div class="title">
      <span class="first-line">有机农作物滞销</span>
      <span class="second-line">救救我们！</span>  
    </div> 

    <p class="description">他会被认为是乐于助人的。    
      <br>
      我想尽可能明智地吃一些更大的东西。</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      uploadData: {
        //这里面放额外携带的参数
      },
    }
  },
  methods: {
    onError(err, file, fileList) {
      this.$store.getters.chunkUploadXhr.forEach(item => {
        item.abort()
      })
      this.$alert('文件上传失败，请重试', '错误', {
        confirmButtonText: '确定'
      })
    },
    beforeRemove(file) {
      // 如果正在分片上传，则取消分片上传
      if (file.percentage !== 100) {
        this.$store.getters.chunkUploadXhr.forEach(item => {
          item.abort()
        })
      }
    }
  }
}
</script>

<style scoped>
.title-content {
  position: relative;  
}

.title-content img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

 .title-content .title {
  position: absolute;
  left: 300px; 
  top: 100px;
  color: #fff;
  font-size: 36px; 
  text-align: left;
  font-weight: bold; 
}

.first-line {
  display: block; 
}

.second-line {
  display: block;
  margin-top: 5px; 
  font-size: 36px;
}

.read-more-btn {
  position: absolute;
  /* left: 300px; 
  bottom: 60px;*/
  padding: 10px 15px;   
  margin-top: 30px; 
  background: #ffb700;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

 .title-content .description {
  position: absolute; 
  right: 300px;
  top: 200px;
  color: #fff;
  font-size: 14px;
  text-align: left;
} 
</style>
