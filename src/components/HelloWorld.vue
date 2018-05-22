<template>
  <div class="hello">
  </div>
</template>

<script>
    import { MessageBox } from 'mint-ui';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  created(){

      MessageBox({
          title: '提示',
          message: '确定执行此操作吗?',
          showCancelButton: true
      });

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  $myColor: yellow;
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: $myColor;
}
</style>
