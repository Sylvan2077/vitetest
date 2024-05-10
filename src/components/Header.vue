<template>
  <header>
    <h1>Agrow<span style="color: #ffa200;">farm</span></h1>

    <div class="daohang">
      <p>主页</p>
      <p>关于</p>
      <p>服务</p>
      <p>联系方式</p>
    </div>

    <div class="search">
    <!-- 搜索框 -->
    <input type="text" placeholder="搜索...">
    <button>搜索</button>
    </div>
  </header>  
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
header {
  background-color: #f5f5f5;
  color: #fff;
  height: 60px;
  display: flex;
  align-items: center;
}

h1 {
  color: black;
  margin-left: 250px; 
  padding: 0 20px;
  font-size: 1.2rem;
}

.daohang {
  display: flex; 
  margin-left: 100px;
}

.daohang p {
  margin-right: 20px;
  color: #333;
  font-size: 14px;  
}

.daohang p:last-child {
  margin-right: 0; 
}

.daohang p:hover {
  color: #007bff;
}

.search {
  margin-left: auto; 
  margin-right: 150px;
}
.search input {
  padding: 8px;
  border: none;
  border-radius: 2px;
}

.search button {
  padding: 9px 12px;
  background: #ffa200;
  color: #fff;
  border: none;
  border-radius: 2px;
}

</style>