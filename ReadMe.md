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

----------------------------------------------------------------------------------------
# Volume Cloud
These are two volumetric cloud systems.


## Cloud Type
### 1. Blueprint XinixCloudBP <br>
This is a volumetric cloud based on a highly foggy system, developed by me. <br>
#### Feature
1. Look closely without noise.
2. The concentration can be controlled by the volume fog system, or directly by the material.
3. Because the volume fog system is used, the volume of fog can be adjusted for the visible distance.
4. There is no classification chart, and the shape of the cloud is not good-looking.

### 2. Blueprint VolumemetricClouds <br>
This is a volume cloud based on Shader, developed from a big Russian. <br>
#### Feature
1. Look closely at the noise (noise has been eliminated, but now the cloud has a harder border after looking closer, please download the original version in related link 1).
2. Not affected by high fog.
3. Very beautiful.


## How to use it in your project?
You can use one of XinixCloudBP or VolumemetricClouds or use them together.
### 1. Using Blueprint XinixCloudBP
1. Migrate XinixClouds / XinixCloudBP in UE4 to your project.
2. Place XinixCloudBP on the map.
2. Place height fog (ExponentialHeightFog) on ​​the map.
3. Deflect the volume fog (Volgmetric Fog) of this height fog.
4. Increase the visible distance (line of sight) of the volume fog, you can adjust it to 300000.0 to see the effect.
### 2. Using Blueprint VolumemetricClouds
1. Grafting VolumetricClouds / VolumetricClouds.
2. Place VolumetricClouds on the map.

## TODO
1. Add fractal processing to the material of XinixCloudBP
# License
This system complies with the MIT agreement.

# Related Links
1. VolumetricClouds developer: https://www.artstation.com/artwork/GXnrvV <br>
2. Dry ice making tutorial: https://zhuanlan.zhihu.com/p/107016039
