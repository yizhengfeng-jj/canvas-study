### canvas的图像变化和状态保存

#### 解释1
图像的变化一般都是以下几个
- translate(x, y) 水平和垂直的位置
- remote(ang) 旋转角度
- scale(sx,sy) 水平和垂直的缩放

#### 解释2
ctx.translate()也是一个状态值，状态也会叠加，但是他的状态叠加不会被ctx.closePath来解决，因为是变化的状态，所以又对两个新的方法ctx.save()和ctx.restore().这两个表示把状态保存起来,然后再恢复