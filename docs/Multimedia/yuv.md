# 一文读懂YUV采样原理

## 1.颜色编码方式：RGB




## 2.颜色编码方式：YUV
从电视系统中衍生的，黑白电视使用的就是Y数据（明亮值），后来出现了彩色格式，电视节目既需要在黑白电视上播放，又需要在彩色电视上播放，就需要做格式兼容，方法就是增加U和V分量，U和V表示的是色度，起作用是描述影像的色彩及饱和度，它们用于指定像素的颜色。

摄像机录出来的数据就是YUV

## 2.YUV采样格式



[参考链接](https://blog.csdn.net/qq_39575835/article/details/86498161)


## 3.YUV存储格式
plannar 平面格式
先连续存储所有像素点的Y分量，然后存储所有的U分量，最后存储所有的V分量

packed 打包格式
每个像素点的Y、U、V分量是连续交替存储的