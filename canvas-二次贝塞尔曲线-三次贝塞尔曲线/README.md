### canvas二次贝尔曲线，三次贝尔曲线

#### 二次贝尔曲线
ctx.moveTo(x,y) // 起始点
ctx.quadraticCurveTo(x1,y1, x2, y2)
x1, y1是控制点，x2,y2结束点
[二次贝尔曲线网站](http://blogs.sitepointstatic.com/examples/tech/canvas-curves/quadratic-curve.html)

#### 三次贝塞尔曲线
ctx.moveTo(x,y) // 起始点
ctx.bezierCurveTo(x1,y1, x2, y2, x3, y3)
x,y是起始点
x1,y1,x2,y2是控制点
x3,y3是结束点
[三次贝塞尔曲线网站](http://tinyurl.com/html5bezier)