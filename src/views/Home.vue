<template>
  <div class="wrapper">
    <div class="logo">
      <img src="../assets/logo.png" alt="" style="height: 200px">
    </div>
    <div class="type">
      <div class="item">
        <img src="../assets/logo.png" alt="" style="height: 160px">
      </div>
      <div class="item">
        <img src="../assets/logo.png" alt="" style="height: 160px">
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
<style scoped lang="scss">
  .wrapper {
    padding: 20px;
    .logo {
      height: 200px;
      background: #fff;
      border-radius: 10px;
      text-align: center;
    }
    .type {
      margin-top: 20px;
      display: flex;
      justify-content: space-between;
      .item {
        width: calc(50% - 10px);
        height: 200px;
        background: #fff;
        border-radius: 10px;
        text-align: center;
      }
    }
  }
</style>
