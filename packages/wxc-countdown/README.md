# wxc-countdown

> MinUI 小程序组件 - 倒计时

## Install

``` bash
$ min install @minui/wxc-countdown
```

> Please make sure you have installed [Min-Cli](https://github.com/meili/min-cli)☟

```
$ npm install -g @mindev/min-cli
```

For more information about MinUI, please visit [MinUI in Github](https://github.com/meili/minui).


## API

### Countdown【props】

| 名称      | 描述      |
|-----------|-----------|
| countdown | [说明]：倒计时秒数<br>[类型]：`Number`<br>[默认值]：0|
| format | [说明]：展示格式<br>[类型]：`String`<br>[默认值]：dd天hh时mm分ss秒 |
| num-style | [说明]：数字样式<br>[类型]：`String`<br>[默认值]：`""`|
| symbol-style | [说明]：标识或文案样式<br>[类型]：`String`<br>[默认值]：`""` |
| bind:runcount | [说明]：计时事件，每次倒计时1秒触发 |
| bind:endcount | [说明]：结束事件，倒计时结束时触发 |

##  ChangeLog

#### v1.0.1（2017.10.24）

- 初始版本
