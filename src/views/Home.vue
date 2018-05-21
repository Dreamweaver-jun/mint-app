<template>
  <div class="wrapper">
    <div class="logo">
      <img src="../assets/logo.png" alt="" style="height: 200px">
    </div>
    <div class="type">
      <div class="item">
        <img src="../assets/logo.png" alt="" style="height: 160px">
        <p>(0)</p>
        <p>采购审批</p>
      </div>
      <div class="item">
        <img src="../assets/logo.png" alt="" style="height: 160px">
        <p>(0)</p>
        <p>订单审批</p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import { Toast } from 'mint-ui';

export default {
  name: 'home',
  created(){
      this.$nextTick(() => {
          this.$http.post('v2/book/1220562',{}).then((response) => {
              console.log('Data',response);
          }).catch((err) => {
              Toast('网络错误'+err);
          });
      })
  },
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
