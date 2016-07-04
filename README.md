# material-ui-pagination
 
maerial-ui的分页插件。

[material-ui](http://www.material-ui.com/)官网没有提供相应的分页插件，找到一个但是没有文档，所以干脆自己写了一个，第一次写代码有点乱，差不多可以用。

|字段名|类型|默认值|说明|
|-------|-----|------|-----------|
|items|int|0|总页码|
|prev|bool|false|设置为 true 显示 上一页 按钮|
|  first  |bool|false|设置为 true 显示 第一页 按钮|
|  next  |bool|false|设置为 true 显示 下一页 按钮|
|  last  |bool|false|设置为 true 显示 最后一页 按钮|
| warpStyle | object |  | 最外层的样式 |
| maxButton | int | 5 | 显示页码的按钮数量 |
| buttonStyle | object |  | 页码按钮的样式 |
| activePage | int |  | 当前选中的页码 |
| activePageStyle | object |  | 选中页码的样式 |
| onSelect | function |  | 点击页码的回调事件 |
| ellipsis | bool | false | 设置为 true, 当 items > maxButton 时，智能显示 ... 按钮 |