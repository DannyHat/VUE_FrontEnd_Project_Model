<template>
    <div class="title">
    <el-menu
        mode="horizontal"
        background-color="#dee1e6"
        text-color="#333"
        active-text-color="#bfa02b">
        <el-menu-item index="1">处理中心</el-menu-item>
        <el-menu-item index="2">我的工作台</el-menu-item>
        <el-menu-item index="3">消息中心</el-menu-item>
        <el-menu-item index="4">订单管理</el-menu-item>
    </el-menu>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="css" scoped>

    .title {
        position: absolute;
        top: 0px;
        width: 90%;
    }
</style>
