# mint-app
mint-ui demo

# 技术栈
vue-cli3.0 + vue-router + axios + vuex + mint-ui + ES6 + sass

# 1.安装依赖
npm i (确保已安装node.js)

# 2.运行项目 & 打生产包
npm run serve & npm run build

# 目录结构


├─vue.config.js                                //配置文件（自己创建）
│
├─public
│      favicon.ico                             //ico图标
│      index.html                              //index.html
│
└─src                                          //资源目录
    │  App.vue                                 //主框架
    │  main.js                                 //入口文件
    │  router.js                               //路由文件
    │  store.js                                //状态文件 vuex
    │
    ├─assets                                   //资源目录
    │      logo.png                            //logo
    │
    ├─components                               //公共组件目录
    │      HelloWorld.vue                      //测试组件
    │
    └─views                                    //视图目录
            Home.vue                           //首页组件
            Order.vue                          //订单组件
            User.vue                           //我的信息组件

