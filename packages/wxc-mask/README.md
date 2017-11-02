# wxc-mask

> MinUI 小程序组件 - 遮罩层

## Install

``` bash
$ min install @minui/wxc-mask
```

> Please make sure you have installed [Min-Cli](https://github.com/meili/min-cli) ☟

```
$ npm install -g @mindev/min-cli
```

For more information about MinUI, please visit [MinUI in Github](https://github.com/meili/minui).

## API

### Mask【props】
| 名称                  | 描述                         |
|----------------------|------------------------------|
|`status`              | [说明]：控制遮罩层显示隐藏。<br>[类型]：`String`<br>[默认值]：`"hide"` <br>[可选值]：`"hide"`，遮罩层隐藏；`"show"`，遮罩层显示。<br>|
|`opacity`             | [说明]：设置遮罩层的不透明级别。<br>[类型]：`[String,Number]`<br>[默认值]：`"0.6"` <br>   |
|`background-color`    | [说明]：设置遮罩层的颜色。<br>[类型]：`String`<br>[默认值]：`"#000000"` <br>     |
|`locked`              | [说明]：遮罩层是否设置锁定态。<br>[类型]：`[String]`<br>[默认值]：`"hide"` <br>[可选值]：<br>`"true"`，点击遮罩层背景部分不会关闭遮罩（点击子节点部分关闭遮罩）。<br>`"hide"`，点击遮罩层背景部分关闭遮罩（点击子节点部分不会关闭遮罩）。<br>      |
|`content-align`       | [说明]：设置遮罩层 content 定位位置。<br>[类型]：`String`<br>[默认值]：`"tl"` <br>[可选值]：`"tl"`:页面左上角；`"tr"`:页面右上角；`"bl"`:页面左下角；`"br"`:页面右下角。 <br>  |

##  ChangeLog

#### v1.0.2（2017.11.02）

- update .npmignore

#### v1.0.1（2017.10.24）

- 初始版本
