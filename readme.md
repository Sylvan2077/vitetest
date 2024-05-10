# 前端开发学习资料

## 开发工具安装

### nvm

nvm 可以通过命令行快速安装和使用不同版本的 Node.js。

#### 在线安装

使用 curl 或者 wget 下载 nvm 安装脚本并运行：

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```



#### 验证安装

使用以下命令验证 nvm 是否安装成功：

 ```shell
 $ command -v nvm
 nvm
 ```



### Node.js

#### 使用 nvm 安装：

```shell
# 查看可用的Node.js版本
nvm ls-remote
# 安装Node.js v11.0.0版本
nvm install v11.0.0
# 查看当前已安装的Node.js版本
nvm ls
# 使用Node.js v11.0.0版本
nvm use v11.0.0
```

更多关于 nvm 的信息和使用方法可前往  [nvm](https://github.com/nvm-sh/nvm) 开源仓库查看。

#### 验证安装

```shell
$ node -v
v11.0.0
$ npm -v
6.4.1
```

npm 配置淘宝源：

```shell
npm config set registry https://registry.npmmirror.com
```



## 编程语言学习

1. HTML：https://www.w3school.com.cn/html/index.asp
2. CSS：https://www.w3school.com.cn/css/index.asp
3. JavaScript：https://www.w3school.com.cn/js/index.asp
4. Vue.js 官方中文文档：
   + vue2：https://v2.cn.vuejs.org/v2/guide/
   + vue3：https://cn.vuejs.org/guide/quick-start.html
5. Element UI 中文文档：
   + Element UI：https://element.eleme.cn/#/zh-CN/component/installation
   + Element Plus：https://element-plus.org/zh-CN/component/button.html



## 开源项目：

+ vue-element-admin：https://github.com/PanJiaChen/vue-element-admin
+ vue-admin-template：https://github.com/PanJiaChen/vue-admin-template
+ 项目中文文档：https://panjiachen.gitee.io/vue-element-admin-site/zh/guide/
+ 项目配套教程：[手摸手，带你用vue撸后台系列](https://juejin.cn/post/6844903476661583880)

