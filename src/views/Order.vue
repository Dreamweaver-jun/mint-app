<template>
  <div class="wrapper">
    <mt-navbar v-model="selected" class="order-tab">
      <mt-tab-item id="1">待确认</mt-tab-item>
      <mt-tab-item id="2">待发货</mt-tab-item>
      <mt-tab-item id="3">待收货</mt-tab-item>
      <mt-tab-item id="4">所有</mt-tab-item>
    </mt-navbar>

    <!-- tab-container -->
    <mt-tab-container v-model="selected" class="order-content">
      <mt-tab-container-item id="1">
        <div class="search">
          <mt-search v-model="value">
            <mt-cell
                    v-for="(item, index) in result1"
                    :key="index"
                    :title="item.title"
                    :value="item.value">
            </mt-cell>
          </mt-search>
        </div>
      </mt-tab-container-item>
      <mt-tab-container-item id="2">
        <div class="search">
          <mt-search v-model="value">
            <mt-cell
                    v-for="(item, index) in result2"
                    :key="index"
                    :title="item.title"
                    :value="item.value">
            </mt-cell>
          </mt-search>
        </div>
      </mt-tab-container-item>
      <mt-tab-container-item id="3">
        <div class="search">
          <mt-search v-model="value">
            <mt-cell
                    v-for="(item, index) in result3"
                    :key="index"
                    :title="item.title"
                    :value="item.value">
            </mt-cell>
          </mt-search>
        </div>
      </mt-tab-container-item>
      <mt-tab-container-item id="4">
        <div class="search">
          <mt-search v-model="value">
            <mt-cell
                    v-for="(item, index) in result4"
                    :key="index"
                    :title="item.title"
                    :value="item.value">
            </mt-cell>
          </mt-search>
        </div>
      </mt-tab-container-item>
    </mt-tab-container>
  </div>
</template>

<script>

    import { Navbar, TabItem, Search } from 'mint-ui';

    export default {
        name: 'order',
        data(){
            return {
                selected: "1",
                value: '输入订单',
                result1: [
                    {title: '待确认11111', value:11111111},
                    {title: '待确认22222', value:22222222},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                    {title: '待确认33333', value:33333333},
                ],
                result2: [
                    {title: '待发货11111', value:11111111},
                    {title: '待发货22222', value:22222222},
                    {title: '待发货33333', value:33333333}
                ],
                result3: [
                    {title: '待收货11111', value:11111111},
                    {title: '待收货22222', value:22222222},
                    {title: '待收货33333', value:33333333}
                ],
                result4: [
                    {title: '所有11111', value:11111111},
                    {title: '所有22222', value:22222222},
                    {title: '所有33333', value:33333333}
                ]
            }
        },
        components: {
            Navbar, TabItem, Search
        }
    }

</script>

<style scoped lang="scss">
  .wrapper {
    height: 100%;
    overflow: hidden;
    .order-tab {
      height: 50px;
    }
    .order-content {
      height: calc(100% - 50px);
      .search {
        position: relative;
      }
    }
  }

</style>
<style lang="scss">
  .wrapper {
    .order-tab {
      .mint-tab-item.is-selected {
        margin-bottom: 0;
      }
    }
    .order-content {
      .mint-search-list {
        padding: 52px 0 150px 0;
      }
    }
  }
</style>