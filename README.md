# 微信小程序 WePy Sublime 插件

### 使用方法

输入 `wpy` 后按 Tab 会生成如下代码：

```html
<style lang="less"></style>

<template lang="wxml"></template>

<script>
  import wepy from 'wepy'

  export default class Page extends wepy.page {
    data = {}
    onLoad () {
      console.log('onLoad Page...')
    }
  }
</script>

```

输入 `repeat` 后按 Tab 会生成如下代码：

```html
<repeat for="{{list}}" key="index" index="index" item="item"></repeat>
```