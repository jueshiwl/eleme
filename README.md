# eleme
>  本项目是基于vue1实战项目，vue1 + webpack + es6 + eslint 高仿饿了么app , 是适合新手进阶的绝佳教程。

###首先

***
>  * 喜欢的请点心，关注，star ,fork,这些是我坚持下去的动力
>  * demo地址 [demo](http://liangxiaojuan.github.io/elem/index#/goods) （请用chrome的手机模式预览）
>  * 本项目地址[github地址](https://github.com/jueshiwl/eleme)
>  * 我的另外还上传了一个eleme vue2.0的开源项目 [eleme2.0]() 可以让你清楚的看到vue1.0 和vue2.0的区别。


### 项目技术架构
***
*  vue-cli
*  vue
*  vue-resource
*  vue-router
*  better-scroll
*  stylus
*  webpack

###安装
***
项目地址：（`git clone`）
```shell
git clone https://github.com/liangxiaojuan/eleme.git
```
通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
npm install 安装了淘宝镜像的可以使用 cnpm install 速度更快
```
启动服务(http://localhost:3100)

```
npm run dev
```
发布代码

```
npm run build
```
### 安装注意
安装 vue-cli
```
npm install -g vue-cli

```
安装 vue-cli eslint
```
npm install -g eslint
```

###目录结构
***
<pre>
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── assets         // 图片资源
│   ├── common          // 公共的css js 资源
│   ├── components     // 各种组件
│   ├── App.vue         // 主页面 
│   └── main.js        // Webpack 预编译入口
</pre>

###实现的功能
***
* 商品菜单联动
* 加入购物车，移除购物车
* 显示评论 评论筛选
* 图片左右滑动
* 商品详情  父子组件的通信
* 等等

### 最后
***
* 如果喜欢一定要 star哈!!!（谢谢!!）
* 如果有意见和问题 请在 issues提出，我会在线解答。
