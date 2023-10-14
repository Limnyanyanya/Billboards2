<template>
  <!DOCTYPE html>
  <html>
    <head>
<meta charset="utf-8">
<title>Billboards</title>
    </head>
    <body>
      <span>
        <img>    <!--图标-->
        <h1>告示牌</h1>
    </span>
<span><NButton type="success">安装告示牌</NButton>
<NButton  type="tertiary">登录</NButton></span>
<div style="left: auto;">
  <p>欢迎来到Billboards的官方网站！
    我们的目标是做最高效的办公软件，
    帮助大家高效快速的完成任务到点下班。
  </p>
  <p>最好用的通知任务工具</p>
  <div style="padding-left: 24px; position: relative">
  <NH1 prefix="bar" align-text>
    <NText type="primary">
        基于组织
      </NText>
    </NH1>
  </div>
  <div style="padding-left: 24px; position: relative">
  <NH1 prefix="bar" align-text>
    <NText type="primary">
        任务管理
      </NText>
    </NH1>
  </div>
  <div style="padding-left: 24px; position: relative">
  <NH1 prefix="bar" align-text>
    <NText type="primary">
        通知下发
      </NText>
    </NH1>
  </div>
  <div style="padding-left: 24px; position: relative">
  <NH1 prefix="bar" align-text>
    <NText type="primary">
        定时提醒
      </NText>
    </NH1>
  </div>
</div> 
   </body>
    </html>
</template>
<script setup lang="ts">
 import { NButton } from 'naive-ui'
 import { NText } from 'naive-ui'
 import { NH1 } from 'naive-ui'
</script>
<style></style>
