<template>
  <router-view />
</template>

<script lang="ts" setup>
</script>

<style lang="less">
html{
  font-size: 14px;
}
body,div,a,ul,li,input,textarea,section{
  margin: 0;
  padding: 0;
}
body{
  font-family: -apple-system,BlinkMacSystemFont,Helvetica Neue,PingFang SC,Microsoft YaHei,Source Han Sans SC,Noto Sans CJK SC,WenQuanYi Micro Hei,sans-serif;
  overflow: auto !important;
  background-color: #f6f6f6;
  padding-right: 0px !important;
}
.modal-open {
  overflow-y: scroll;
  padding-right: 0 !important;
}
li{
  list-style: none;
}
a{
  text-decoration: none;
}
a:visited,
a:link
{
  color: #000;
}
a:hover{
  cursor: pointer;
}
.isFixed{
  position: fixed;
}
.isShow{
  display: block;
}
.isHidden{
  display: none;
}
.fl{
  float: left;
}
.fr{
  float: right;
}
.clear-both{
  clear: both;
}
.clear-fix::after::before{
  clear: both;
}
.clear-before::before{
  clear: left;
}
.clear-after::after{
  clear: right;
}
.over-h{
  overflow: hidden;
}
.c-8590a6{
  color: #8590a6;
}
.m-0-5{
  margin: 0 5px;
}
.m-0-8{
  margin: 0 8px;
}
.m-0-10{
  margin: 0 10px;
}
.Zi{
  vertical-align: sub;
  margin-right: 5px;
}
.Zi--ArrowDown{
  transform: rotate(180deg) translate(20%,-20%);
  vertical-align: bottom;
}
.Card{
    background-color: #fff;
    padding: 15px;
    box-shadow: 0 1px 1px #e1e1e1,0 2px 1px #f5f5f5;
}
.btn{
  width: fit-content;
  line-height: 30px;
  padding: 0 15px;
  background-color: transparent;
  outline: none;
  border-width: 1px;
  border-style: solid;
  border-radius: 3px;
}
.btn:hover{
  cursor: pointer;
}
.btn-primary{
  color: #fff;
  border-color: #005ce6;
  background-color: #005ce6;
}
.btn-blue{
    color: #06f;
}
.btn-gray{
    color: #8590a6;
}
.btn-white{
  color: #d3d3d3;
}
.ant-popover-inner-content{
  padding: 0!important;
}
.ant-popover{
  position: fixed!important;
}
</style>
