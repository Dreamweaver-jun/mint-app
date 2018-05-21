<template>
  <div id="app">
    <router-view/>
    <div id="nav">
      <router-link to="/">
        <div class="ico"></div>
        <p>首页</p>
      </router-link>
      <router-link to="/order">
        <div class="ico"></div>
        <p>订单</p>
      </router-link>
      <router-link to="/user">
        <div class="ico"></div>
        <p>我的信息</p>
      </router-link>
    </div>
  </div>
</template>

<style lang="scss">

  /** reset START **/
  p, ul, li, body, a,a:after, a:focus, a:visited, a:hover, a:active, article, aside, footer, header, hgroup, main, nav, section {
    margin: 0;
    padding: 0;
    font-size: 14px;
    text-decoration: none;
    box-sizing: border-box;
    list-style: none;
    font-family: Helvetica;
  }
  html,body,#app {
    height: 100%;
    background: #edebe9;
  }
  /** reset END **/

#nav {
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 60px;
  background: #fff;
  box-shadow: 0 0 15px 5px #cdcdcd;
  display: flex;
  justify-content: space-around;
  align-items: center;
  a {
    display: block;
    width: 100%;
    text-align: center;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
      .ico {
        background: #42b983;
      }
    }
    .ico {
      display: inline-block;
      width: 30px;
      height: 30px;
      background: #666;
    }
  }
}
</style>
