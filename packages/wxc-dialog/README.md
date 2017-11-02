# wxc-dialog

> MinUI 小程序组件 - 对话框

## Install

``` bash
$ min install @minui/wxc-dialog
```

> Please make sure you have installed [Min-Cli](https://github.com/meili/min-cli)☟

```
$ npm install -g @mindev/min-cli
```

For more information about MinUI, please visit [MinUI in Github](https://github.com/meili/minui).


## API

### Dialog【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`title`           | 【说明】标题文案<br>【类型】`String`<br>【默认值】`""`   |
|`title-color`      | 【说明】标题颜色<br>【类型】`String`<br>【默认值】`#000000`    |
|`content`         | 【说明】内容 <br>【类型】`String`<br>【默认值】`""`       |
|`content-color`    | 【说明】内容颜色<br>【类型】`String`<br>【默认值】`#888888`      |
|`confirm-text`     | 【说明】确认按钮文案 <br>【类型】`String`<br>【默认值】`""`               |
|`confirm-color`    | 【说明】确认按钮文案颜色<br>【类型】`String`<br>【默认值】`#ff5777`  |
|`cancel-text`      | 【说明】取消按钮文案   <br>【类型】`String`<br>【默认值】`""`           |
|`cancel-color`     | 【说明】取消按钮文案颜色<br>【类型】`String`<br>【默认值】`#666666`  |
|`image`           | 【说明】显示的图片链接     <br>【类型】`String`<br>【默认值】`""`              |


### Dialog【methods】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`show`         | 【说明】显示弹窗<br>【params】void<br>【return】void        |
|`hide`			| 【说明】隐藏弹窗<br>【params】void<br>【return】void		|


##  ChangeLog

#### v1.0.1（2017.10.24）

- 初始版本
