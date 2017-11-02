# wxc-price

> MinUI 小程序组件 - 价格

## Install

``` bash
$ min install @minui/wxc-price
```

> Please make sure you have installed [Min-Cli](https://github.com/meili/min-cli)☟

```
$ npm install -g @mindev/min-cli
```

For more information about MinUI, please visit [MinUI in Github](https://github.com/meili/minui).


## API

### Price【props】

| 属性 | 描述 |
| --- | --- |
| value | [可选] 价格数值，优先级高于标签内嵌套值 |
| status | [可选] 显示状态，若设置为 del 显示为删除态 |
| icon | [可选] 人民币符号显示规则 <br/><br/> - 如不设置，人民币符号的字号同价格数字一致 <br/> - 设为 sup，人民币符号字号缩小，位于价格左上方 <br/> - 设为 sub，人民币符号字号缩小，位于价格左下方 |
| decimal | [可选] 小数部分显示规则 <br/><br/> - 如不设置，显示 2 位小数，字号同整数部分一致 <br/> - 设置为 1，显示 1 位小数，小数部分向下取整 <br/> - 设为 none，不显示小数部分，只显示整数价格 <br/> - 设为 small，小数部分字号缩小|

##  ChangeLog

#### v1.0.1（2017.10.24）

- 初始版本
