<template>
    <div class="content">
        <div class="app-wrapper">
            <el-menu class="leftgrid"
                     background-color="#545c64"
                     text-color="#fff"
                     active-text-color="#ffd04b">
                <el-menu-item index="1">
                    <i class="el-icon-location"></i>
                    <span>导航一</span>
                </el-menu-item>
                <el-menu-item index="2">
                    <i class="el-icon-menu"></i>
                    <span slot="title">导航二</span>
                </el-menu-item>
                <el-menu-item index="3">
                    <i class="el-icon-document"></i>
                    <span slot="title">导航三</span>
                </el-menu-item>
                <el-menu-item index="4">
                    <i class="el-icon-setting"></i>
                    <span slot="title">导航四</span>
                </el-menu-item>
            </el-menu>
        </div>
        <div class="right_content">
            <hello-world>111</hello-world>
        </div>
    </div>

</template>
<script>
import HelloWorld from './HelloWorld.vue'
export default {
  components: {HelloWorld},
  data () {
    return {}
  },
  methods: {},
  computed: {},
  watch: {},
  created () {
  },
  mounted () {
  }
}
</script>
<style lang="css" scoped>
@import url("//unpkg.com/element-ui@2.2.2/lib/theme-chalk/index.css");
.content {
    text-align: left;
    width: 100%;
    height: 100%;
}
.app-wrapper {
    width: 10%;
    padding-left: 0px;
    height: 100%;
    padding-right: 0px;
    background-color: rgb(84, 92, 100);
    display: inline-block;
    text-align: left;
}
.right_content {
    display: inline-block;
    float: right;
    padding-left: 0px;
    border-width: 0px;
    width: 90%;
}
ul {
   text-align: left;
   margin: 0px;
   background-color: rgb(84, 92, 100);
   border: 0px;
}
li {
    padding-left: 0px;
}
el-menu-item {
    padding: 0px;
}
</style>
