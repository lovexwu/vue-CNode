**预览地址:** https://lovexwu.github.io/vue-CNode/#/

## 项目功能
高仿CNODE社区

## 项目模块组件： 
1､Header模块  
2､PostList模块  
3､Article模块  
4､Slider侧边栏模块  
5､UserInfo用户个人中心模块  
6､Pagination分页组件的开发  

## 项目技术
1､vue.js计算属性  
2､vue.js的内置指令和事件的绑定  
3､vue.js的自定义事件和触发  
4､vue-router路由的跳转和监听  
5､父子组件之间的数据传递  

## 遇到的坑
上传到github，并通过Github pages预览时，由于文件路径原因，页面404显示，需要修改配置
**打开项目根目录config文件夹下的index.js文件**，进行如下修改

![image.png](https://upload-images.jianshu.io/upload_images/14339384-1865b3c28f6bdc5b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**切记是index.js中的build下的 assetsPublicPath ：将‘/'改为‘./'**
【文件上边还有个dev 是开发环境下的配置，不需要改动】


## 技术栈
vue-cli、vue2､axios、vue-router、vuex、es6､npm
