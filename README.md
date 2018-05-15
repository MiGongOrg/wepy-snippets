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

###### 视图容器

| 命令         | 说明          |
|-------------|--------------|
| wview       | 视图容器       |
| wscroll     | 可滚动视图区域  |
| wswiper     | 滑块视图容器    |
| wmovable    | 可移动的视图容器 |
| wcoverview  | 覆盖在原生组件之上的文本视图 |
| wcoverimage | 覆盖在原生组件之上的图片视图 |

###### 基础内容

| 命令       | 说明      |
|-----------|----------|
| wicon     | Icon 图标 |
| wtext     | 文本      |
| wrichtext | 富文本    |
| wprogress | 进度条    |
