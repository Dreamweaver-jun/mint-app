<template>
  <div class="wrapper">
    <div class="person-info">
      <mt-cell title="用户姓名" value="隔壁老王"></mt-cell>
      <mt-cell title="手机号码" value="13888888888"></mt-cell>
      <mt-cell title="电子邮箱" value="123456@126.com"></mt-cell>
    </div>
    <div class="company-info">
      <mt-cell title="所属医院" value="中山大学附属肿瘤医院"></mt-cell>
      <mt-cell title="工作部门" value="老王课题组"></mt-cell>
    </div>
    <div class="statistical-info">
      <mt-cell title="医院订单统计" value=""></mt-cell>
      <mt-cell title="课题组订单统计" to="/" is-link value=""></mt-cell>
    </div>
    <div class="setting">
      <mt-cell title="设置" to="/" is-link value=""></mt-cell>
    </div>
  </div>
</template>

<script>

    import { Cell } from 'mint-ui';

    export default {
        name: 'user',
        components: {
            Cell
        }
    }

</script>

<style scoped lang="scss">
  .wrapper {
    .person-info,.company-info,.statistical-info {
      margin-bottom: 20px;
    }
  }
</style>
<style lang="scss">
  .wrapper {
    .mint-cell-wrapper {
      background-image: none;
      border-bottom: 1px solid #eee;
    }
  }
</style>