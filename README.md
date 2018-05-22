# mint-app
mint-ui demo

# 技术栈
vue-cli3.0 + vue-router + axios + vuex + mint-ui + ES6 + sass

# 1.安装依赖
npm i (确保已安装node.js)

# 2.运行项目 & 打生产包
npm run serve & npm run build

# 目录结构


<p>
    ├─vue.config.js&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //配置文件（自己创建）
</p>
<p>
    │
</p>
<p>
    ├─public
</p>
<p>
    │&nbsp; &nbsp; &nbsp; favicon.ico&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//ico图标
</p>
<p>
    │&nbsp; &nbsp; &nbsp; index.html&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //index.html
</p>
<p>
    │
</p>
<pre class="brush:html;toolbar:false"><br/></pre>
<p>
    └─src&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //资源目录
</p>
<p>
    &nbsp; &nbsp; │&nbsp; App.vue&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//主框架
</p>
<p>
    &nbsp; &nbsp; │&nbsp; main.js&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//入口文件
</p>
<p>
    &nbsp; &nbsp; │&nbsp; router.js&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//路由文件
</p>
<p>
    &nbsp; &nbsp; │&nbsp; store.js&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //状态文件 vuex
</p>
<p>
    &nbsp; &nbsp; │
</p>
<p>
    &nbsp; &nbsp; ├─assets&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//资源目录
</p>
<p>
    &nbsp; &nbsp; │&nbsp; &nbsp; &nbsp; logo.png&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //logo
</p>
<p>
    &nbsp; &nbsp; │
</p>
<p>
    &nbsp; &nbsp; ├─components&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//公共组件目录
</p>
<p>
    &nbsp; &nbsp; │&nbsp; &nbsp; &nbsp; HelloWorld.vue&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //测试组件
</p>
<p>
    &nbsp; &nbsp; │
</p>
<p>
    &nbsp; &nbsp; └─views&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //视图目录
</p>
<p>
    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Home.vue&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//首页组件
</p>
<p>
    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Order.vue&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; //订单组件
</p>
<p>
    &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; User.vue&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;//我的信息组件
</p>
<p>
    <br/>
</p>
