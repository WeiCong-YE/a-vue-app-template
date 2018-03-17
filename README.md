# 项目简介
    这是一个基于vue-cli的全家桶示例项目，使用了vue-cli作为脚手架搭建，使用了mint-ui作为前端框架。
    路由管理:vue-router，状态管理:vuex，网络请求:axios。
    这是一个移动端的app项目示例，可根据此例进行一个H5应用的搭建，利用打包工具（如cordova）可以打包成原生应用。
    项目的默认端口是`8899`，你也可以在webpack的配置中自己更改。
# 项目运行
    git clone https://github.com/JerryYuanJ/a-vue-app-template.git
    cd a-vue-app-template
    (安装依赖) npm install (或者cnpm install)
    (运行）npm run dev 
    (打包）npm run build
# 功能介绍
    * mint-ui中较为复杂组件的使用，比如loadmore和swipe组件的结合使用，完成主流app列表页的上拉加载更多、下拉刷新、左滑切出编辑选项等常见需求。
    * mint-ui中MessageBox的校验问题解决
    * 子路由的使用
    * echarts图的使用
    * 组件化开发，包括组件开发的常见问题的解决
    * 子路由的应用，以及刷新当前子路由页面的问题解决
# 更新日志
    * ~2018-03-13
      项目搭建及部分代码调整，组件学习、测试等。
    * 2018-03-14
      * 添加sass作为项目的css语言，并且定义了几个共有的变量和混合作为简单学习
      * 添加echarts图的主要统计图表，利用子路由完成单页面内的图表切换。同时解决了单页面内刷新当前子路由的对应组件的展示问题。
    * 2018-03-17
      * 添加下拉刷新组件。自己写的一个组件，实现了下拉刷新功能，主要是探究类似组件的实现原理。
# 博客
这个是我的个人博客，里面有对本项目的详细介绍及搭建，组件学习。每次大的更新都会做相应的记录。
[Jerry的个人博客](http://blog.csdn.net/qq_25324335/article/details/78675148)
# 项目演示    
![项目演示图](http://img.blog.csdn.net/20180317195826324?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMjUzMjQzMzU=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)  
