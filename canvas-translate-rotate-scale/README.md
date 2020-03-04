### canvas-translate-rotate-scale

#### 解释1
在这里主要将一下scale函数，这个函数放大的时候，会把strokeRect的坐标和线条宽度一起放大，解决方法是，先让坐标和线宽对应的缩小
，在放大就没事了