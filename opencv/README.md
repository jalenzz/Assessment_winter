# TaskOfOpencv

主要考察大家对OpenCV基本操作的理解

## 任务1描述
> 有一张放在珍珠棉上的口罩的图片，需要大家能够实现下面这样的效果

**将img里面的src.jpg**

转换为

![](https://github.com/nishangyumei/Assessment/blob/main/opencv/assets/result.jpg?raw=true)
## 可能用到的知识点
1. CMake
   + 这个就不多说了，可以直接百度
2. OpenCV（**这里只是提供思路，可能有别的方法也能做到同样的效果**）
   + 读写图片（tips: 注意可执行文件和图片相对路径的问题）
   + 二值化
   + 形态学滤波
   + 图像轮廓提取
   + 拟合多边形
   + 凸包检测
   + 透视变换

## 提供的参数
口罩的长宽比大致为 17:9


## 任务2描述：
识别装甲板，我们在RM赛场总要识别装甲板，由于分为红蓝双方我们需要对灯条进行判断，实现图片中的功能
原图片：

![](https://img-blog.csdnimg.cn/ad7c029bf2674677b05faaa8f8b221f6.gif)


实现像下面一样的效果：


![](https://img-blog.csdnimg.cn/635ac48f3dbd4c63a112719fd7c90936.gif)

**这里只是提供思路，可能有别的方法也能做到同样的效果**
   + 读写图片（tips: 注意可执行文件和图片相对路径的问题）
   + 二值化
   + 形态学滤波
   + 图像轮廓提取
   + 通道相减
   


