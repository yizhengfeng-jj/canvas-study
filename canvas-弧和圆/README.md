### 弧和圆

#### 解释1
画弧和圆其实是一样的都是用arc函数
arc(x, y, r, start, end, flag);
arc函数的参数介绍,
x,y 表示圆心的位置,
r 表示圆心的半径,
start, end,表示起始角和终止角（0-2PI）,
flag表示画图方向，不设置的话默认是flase，即顺时针方向

#### 解释2
```javascript
canvas.style.width = '60opx';
canvas.style.height = '600px';
canvas.width = 600 * 4;
canvas.height = 600 * 4;
ctx.scale(4, 4); // 以上代码解决了canvas画圆弧的锯齿问题
```