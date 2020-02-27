### 线条 矩形 七巧板
#### 解释1
画线需要两个点，一个起点， 一个终点。分别是moveTo和lineTo

ctx.moveTo();
ctx.lineTo();

然后以上两个是状态点，需要一个执行函数，这个是画线的
ctx.stroke(); 

填充使用ctx.fill()

#### 解释2
画线和填充可以设置颜色和宽度的
ctx.lineWidth = 5; 线条宽度


设置线条颜色和填充颜色
ctx.strokeStyle ='red';
ctx.fillStyle = 'red';


#### 解释三
ctx.beginPath();
ctx.closePath();

以上两个可以指定画图区间，并且closePath()可以自动帮你闭合，前提是放在ctx.stroke()前面


#### 解释四
七巧板的思路是，找到所有点信息，一定是按照某一方找的，不要跳，然后就是循环画矩形