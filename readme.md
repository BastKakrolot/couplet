# 网页春联
**0.1.0 更新**
- 添加龙年图片元素
- 去除阴影

## use

```html
<dragon-couplet
    first-line="龙行大运" // 上联
    second-line="前程似锦" // 下联
    central-line="恭迎新春" // 横批
    reverse // 是否从右往左
    style={{
        '--offset-top': '2px', // 横批距离页面顶部的偏移量
        '--couplet-size': '30px', // 文字大小
        '--offset-out': '2px', // 上、下联距离左右的偏移量
        '--font-family': 'SFZT' // 字体
    }}
></dragon-couplet>
```
