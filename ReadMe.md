# 体积云
这是两个体积云系统。


## 云类型
### 1.蓝图XinixCloudBP<br>
这是基于高度雾系统的体积云，开发自本萌新。<br>
#### 特征
1. 靠近看没有噪点。
2. 可通过体积雾系统控制浓度，也可直接通过材质控制浓度。
3. 因为使用的是体积雾系统，所以可视距离可由体积雾调整。
4. 没有分型图，云的形状不好看。

### 2.蓝图VolumetricClouds<br>
这是基于Shader的体积云，开发自一位俄罗斯大佬。<br>
#### 特征
1. 靠近看有噪点（已去除噪点，但现在靠近看之后云会有比较硬的边界，原版请在相关链接1中下载）。
2. 不受高度雾影响。
3. 很漂亮。


## 怎么在你的项目中使用？
你可以使用XinixCloudBP或VolumetricClouds其中之一，或者一起使用。
### 1.使用蓝图XinixCloudBP
1. 在UE4中移植XinixClouds/XinixCloudBP到你的项目里。
2. 在地图上放置XinixCloudBP。
2. 在地图上放置高度雾（ExponentialHeightFog）。
3. 勾选该高度雾的体积雾（Volumetric Fog）。
4. 调高体积雾的可视距离（View Distance），可以调到300000.0看下效果。
### 2.使用蓝图VolumetricClouds
1. 移植VolumetricClouds/VolumetricClouds。
2. 在地图上放置VolumetricClouds。

## TODO
1.XinixCloudBP的材质添加分形处理
# 协议
本系统遵循MIT协议。

# 相关链接
1. VolumetricClouds开发者：https://www.artstation.com/artwork/GXnrvV<br>
2. 干冰制作教程：https://zhuanlan.zhihu.com/p/107016039
