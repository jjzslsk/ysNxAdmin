<template>
  <div id="app">
        <!--登入动画-->
    <transition name="rotate-fall">
    <router-view  class="app-router-view"></router-view>
    </transition>

  <!-- <body class="hold-transition skin-blue sidebar-mini">
     <div class="wrapper"> -->

        <!-- 左侧导航 -->
        <!-- <main-sidebar></main-sidebar> -->

        <!-- 上部色条 -->
        <!-- <header-top></header-top> -->

        <!-- 下部 -->
        <!-- <content-wrapper></content-wrapper> -->

        <!-- 底部版权 -->
        <!-- <main-footer></main-footer> -->

        <!-- 右侧导航 -->        
        <!-- <control-sidebar></control-sidebar> -->
        
        <!-- 右侧导航必须的 背景颜色 -->
        <!-- <div class="control-sidebar-bg"></div>
      </div>
  </body> -->
  </div>
</template>
<script>
import { mainSidebar,contentWrapper,mainFooter,controlSidebar,headerTop } from './components/Modular/'
export default {
  name: 'App',
    components: {
      headerTop,
    mainSidebar,
    contentWrapper,
    mainFooter,
    controlSidebar
  },
}
  // $.widget.bridge('uibutton', $.ui.button);

</script>
<style>
.tree-row .el-tree-node{
  background: #f5f7fa;
}
.tree-row .el-tree-node__children .el-tree-node{
  float: left;
}
.tree-row .el-tree-node__content {
  /* background: beige; */
}
#app .sidebar-container .svg-icon {
    margin-right: 0px;
}
.el-submenu .el-menu-item {
    padding: 0 0px;

}.el-submenu .el-menu-item .pull-right-container{
    height: 50px;
    display: flex;
    float: right;
    align-items: center;
    margin-right: 2rem;
}
/* .sectionBox .el-dialog__body {
    padding: 0;
} */
.sectionBox .el-card__body {
    padding: 0;
} 
.sectionBox .el-form--inline .el-form-item {
    margin-right: 1px;
}
.box-cardBox .el-card__body{
  padding: 0px;
}
.roleCard .el-card__body {
  padding: 1rem
}
.tablesSyl td, .tablesSyl th{
  padding: 5px 0
}
.el-dialog__header {
    background: #222d32;
}
.el-dialog__title {
  color: #fff;
}
.el-table thead {
    color: #000;
}
.el-table {
    color: #000;
}
.tablesSyl .cell{
      min-width: 8rem;
}
.el-dialog__headerbtn .el-dialog__close {
    color: #fff;
    font-size: 2rem;
}
.sectionBox .el-button--info {
    color: #fff;
    background-color: #2c3e50;
    border-color: #2c3e50;
}
.sectionBox .el-button--info.is-disabled, .el-button--info.is-disabled:active, .el-button--info.is-disabled:focus, .el-button--info.is-disabled:hover {
    color: #fff;
    background-color: #c8c9cc;
    border-color: #c8c9cc;
}
.el-dropdown-menu .el-checkbox {
  display: block;
  padding: 0rem 2rem;
}
.el-dropdown-menu .el-checkbox+.el-checkbox {
    margin-left: 0px;
}
  .box-cardBox .el-form-item--small .el-form-item__content{
    height: 41px;
    line-height: 41px;
  }
  .transferBox .el-transfer__buttons {
  padding: 0;
}
  .transferBox .el-transfer__buttons .el-button+.el-button{
  margin-left:0;
}
  .transferBox .el-transfer__buttons .el-button{
  padding: 5px 10px;
  display: block;
}
.transferBox .el-transfer-panel__filter {
  margin: 1rem 0 0 0;
}
.transferBox .el-checkbox+.el-checkbox {
    margin-left: 0;
}
.transferBox .el-transfer-panel__filter .el-input__inner {
  width: 90%;
}
.transferWrap .el-dialog__body{
  line-height: 0px;
  /* padding: 30px 20px 0 20px; */
} 
.transferWrap .el-dialog__body .transferBox label{
  margin-bottom: 0px;
} 
.transferBox .el-transfer-panel__footer {
  display: none;
}
</style>
