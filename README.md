# my-blog

> 一套全新前端页面

### 线上demo

[在线体验](http://vue.haoht123.com/)

# 项目布局

```
├─ build								// webpack配置文件
├─ config								// 项目打包路径
├─ src									// 源码目录
│    ├─ App.vue							// 页面入口文件
│    ├─ assets							// 公共资源
│    ├─ common							//通用配置文件
│    │    ├─ config.js					//接口域名配置
│    │    └─ http.js					//请求方法封装
│    ├─ components						//通用组件
│    │    ├─ Footer.vue					//页脚公共组件
│    │    ├─ Header.vue					//页眉公共组件
│    │    ├─ NotFound.vue				//404公共组件
│    │    ├─ SectionArticle.vue			//首页列表公共组件
│    │    └─ index.js					//统一导出页眉页脚和404组件
│    ├─ element							//按需引入elementUI组件
│    ├─ main.js							// 程序入口文件，加载各种公共组件
│    ├─ router							
│    │    └─ index.js					//路由配置
│    ├─ store							
│    │    └─ index.js					//实例store，mutations
│    └─ views
│           ├─ About					//关于我们页面
│           ├─ Blog						//文章详情页面
│           ├─ Categories				//分类详情页面
│           ├─ Everyday					//每日一图页面
│           ├─ Home						//首页
│           └─ Tags						//标签详情页
│           └─ Tags						//标签详情页
├─ index.html							// 入口html文件
├─ package.json							//依赖文件

```
## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
