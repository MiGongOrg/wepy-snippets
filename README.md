# 微信小程序 WePy Sublime 插件

| Wepy Page                 | 小程序组件                     |
|---------------------------|------------------------------|
|<img src="./demo/page.gif">|<img src="./demo/movable.gif">|

微信小程序 WePy Sublime 插件，集成部分 WePy 可复用代码块，整合小程序组件并生成代码片段。使用 WePy Snippets 开发小程序将变得更高效。

#### 安装方法

##### 1.前往指定目录

```sh
Nix: ~/.config/sublime-text-3/packages
Mac: ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
Win: %APPDATA%\Sublime Text 3\Packages
```

##### 2.clone 该项目到该目录

```sh
git clone https://github.com/MiGongOrg/wepy-snippets.git 'wepy-snippets'
```

#### 使用方法

> 输入相应命令后按 `Tab`

**注：** 如果没有自动提示，请设置用户配置文件 `Preferences` - `Settings`

```
"auto_complete_selector": true
```

##### WePy

| 命令        | 说明            |
|------------|----------------|
| wpage      | wepy page      |
| wcomponent | wepy component |
| wrepeat    | wepy repeat    |

##### 小程序组件

###### 视图容器组件

| 命令          | 说明          |
|--------------|--------------|
| wview        | 视图容器       |
| wscrollview  | 可滚动视图区域  |
| wswiper      | 滑块视图容器    |
| wmovableview | 可移动的视图容器 |
| wcoverview   | 覆盖在原生组件之上的文本视图 |
| wcoverimage  | 覆盖在原生组件之上的图片视图 |

###### 基础内容组件

| 命令       | 说明      |
|-----------|----------|
| wicon     | Icon 图标 |
| wtext     | 文本      |
| wrichtext | 富文本    |
| wprogress | 进度条    |

###### 表单组件

| 命令               | 说明      |
|-------------------|----------|
| wbutton           | 按钮      |
| wcheckbox         | 多项选择器 |
| wform             | form 表单 |
| winput            | 输入框    |
| wlabel            | 标签      |
| wpicker           | 选择器    |
| wpickerview       | 滚动选择器 |
| wpickerviewcolumn | 选择列    |
| wradio            | 单项选择器 |
| wslider           | 滑动选择器 |
| wswitch           | 开关选择器 |
| wtextarea         | 多行输入框 |

###### 导航组件

| 命令        | 说明    |
|------------|--------|
| wnavigator | 页面链接 |

###### 媒体组件

| 命令         | 说明    |
|-------------|--------|
| waudio      | 页面链接 |
| wimage      | 图片    |
| wvideo      | 视频    |
| wwcamera    | 系统相机 |
| wliveplayer | 实时音视频播放 |
| wlivepusher | 实时音视频录制 |

###### 地图组件

| 命令  | 说明 |
|------|-----|
| wmap | 地图 |

###### 画布组件

| 命令     | 说明 |
|---------|-----|
| wcanvas | 画布 |

###### 开放能力

| 命令       | 说明    |
|-----------|--------|
| wopendata | 开放数据 |
| wwebview  | 网页容器 |
