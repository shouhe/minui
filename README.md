# MinUI

基于规范的小程序 UI 组件库，轻量、易用、工具化。

![](https://img.shields.io/badge/Build-Passing-brightgreen.svg) ![](https://img.shields.io/badge/License-MIT-lightgrey.svg) ![](https://img.shields.io/badge/%E5%9F%BA%E7%A1%80%E5%BA%93-1.6.0%2B-brightgreen.svg) ![](https://img.shields.io/badge/Powered%20by-Min-28b1b0.svg)

![](http://s3.mogucdn.com/mlcdn/c45406/171101_850g622e33552bb75f74ael4k563f_3882x1734.png_1200x999.jpg)

![](http://s3.mogucdn.com/mlcdn/c45406/171025_00h0heed7c1a5iid87ch299h3l8j4_3882x1734.png_1200x999.jpg)

### ○ 缘起

一切的初衷，都始于我们希望像下面这样，在小程序中优雅的定义和使用组件。

<img width="404" src="https://s10.mogucdn.com/mlcdn/c45406/171101_5jji6el984agkfl47454i2h34ej88_808x425.png" style="display:block;margin:0 auto;" />

于是我们设计了 **[Min](https://github.com/meili/min-cli)**。

Min 是一套面向小程序的开发环境，提供 [Min Cli](https://github.com/meili/min-cli)。目前，我们[开源](https://github.com/meili/min-cli)了它面向小程序自定义组件的部分（后续还会陆续开源其他能力），结合微信开发者工具，对组件的 **开发** 和 **使用**，Min 会让你感到优雅和高效。

而 MinUI，就是基于 Min 平台产出的一套 UI 组件库，同时也是蘑菇街小程序在应用的 UI 组件库。

### ○ 体验

#### 在线体验

通过下面的小程序二维码，可以在手机中体验 MinUI（微信基础库版本 1.6.3 以上支持）：

<img width="200" src="https://s10.mogucdn.com/mlcdn/c45406/171101_6k682blbc5j30lj08galbk1k0g95h_1280x1280.jpg" style="display:block;margin:0 auto;" />

> 注：如提示“小程序尚未发布”，就再等等再扫 :p

#### 本地体验

1. 安装 Min 的环境 `$ npm install -g @mindev/min-cli`
2. Clone MinUI 仓库到本地；
3. 终端在 MinUI 根目录下执行 `$ min dev`，生成 dist/ 目录；
4. 微信开发者工具 —— 新建一个小程序，目录指向生成的 dist/；
5. Done~

PS：如想尝试修改源码，终端里先执行 `$ min dev`。这样任何的修改，都会在微信开发者工具中自动刷新显示。

#### 开发&应用

如要基于 MinUI 进行二次开发，完善属于您项目的组件化体系，请移步至 Min 的使用文档 —— “组件开发” 环节。

如要在既有小程序项目中，使用 Min 提供的组件安装和更新能力，请移步至 Min 的使用文档 —— “组件应用” 环节。

### ○ 组件列表


```
- 布局元素
    - flex
    - card（coming...）
    - list（coming...）
- 基础元件
    - badge
    - elip
    - icon
    - label
    - loadmore
    - price
    - progress
- 功能组件
    - abnor
    - countdown
    - couner
    - loading
    - mask
    - steps
    - tab
- 提示反馈
    - dialog
    - popup
    - toast
- 表单增强（coming...）
```
### ○ 项目结构

```
- MinUI/
    - dist // 打包目录，在微信开发者工具中添加这个目录来运行项目
    - packages // 组件目录
        - loading
            - src
                - index.wxc // 组件单文件
            - .npmignore
            - package.json
            - README.md
            - LICENSE
        - ...
    - src // 页面源码
        - common
        - pages // 组件 demo 页面
            - loading
                - demos // demo 汇总，在 index.wxp 中引入和显示
                - config.json
                - index.wxp
            - ...
    - .editorconfig
    - .gitignore
    - LICENSE
    - min.config.json
    - package.json
    - README.md
```

更多项目结构介绍，可参考工具化 Min Cli 提供的[工程说明](https://github.com/meili/min-cli)。

### ○ 开源协议

本项目基于 [MIT](http://opensource.org/licenses/MIT) License，请自由的享受、参与开源。


### ○ 更新记录

#### v1.0.0（2017.10.24）

- 初始版本
