# canvas-nest-pc.js
使用 canvas-nest.js 1.0.1 代码，增添 PC 判断功能，让 canvas-nest.js 仅在 PC 端生效。

canvas-nest.js 链接：https://github.com/hustcc/canvas-nest.js

## 使用

将下面的代码插入到 `<body> 和 </body> 之间`.

```html
<script type="text/javascript" src="./canvas-nest.js"></script>
```

强烈建议在 `</body>`标签上方. 例如下面的代码结构:

```html
<html>
<head>
	...
</head>
<body>
	...
	...
	<script type="text/javascript" src="./canvas-nest.js"></script>
</body>
</html>
```

然后就完成了，打开网页即可看到效果!`请注意不要将代码置于 <head> </head>里面`.


## 配置

 - **`color`**: 线条颜色, 默认: `'0,0,0'` ；三个数字分别为(R,G,B)，注意用,分割
 - **`pointColor`**: 交点颜色, 默认: `'0,0,0'` ；三个数字分别为(R,G,B)，注意用,分割
 - **`opacity`**: 线条透明度（0~1）, 默认: `0.5`
 - **`count`**: 线条的总数量, 默认: `150`
 - **`zIndex`**: 背景的z-index属性，css属性用于控制所在层的位置, 默认: `-1`

Example:
```html
<script type="text/javascript" color="0,0,255" opacity='0.7' zIndex="-2" count="99" src="./canvas-nest.js"></script>
```
