### canvas-线条的帽子

#### 解释 1

在这节学习里面，主要总结了以下 lineCap 的用法，有三种形式
lineCap: 
- butt(default)默认形式，默认是没有帽子的
- round, 有一个突出的圆形帽子
- square, 有一个突出的方形帽子

#### 解释 2

lineCap 如果应用在多边形上的话，只会在开始和结尾处有效果。并且 lineCap: square.还能解决线条宽度过大，首位连接出现间隙问题，但是推荐的做法还是用 closePath()去做;
