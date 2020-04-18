# Volume Cloud/体积云

Two volume cloud implementations on Unreal Engine 4.<br>在虚幻引擎4上的两种体积云实现。

***

### Cloud Type/云类型

#### Blueprint XinixCloudBP/基于蓝图的XinixCloudBP

This is a volumetric cloud based on a highly foggy system, developed by me. <br>这是基于高度雾系统的体积云，开发自本萌新。

##### Feature/特性

* Look closely without noise.<br>靠近看没有噪点。

* The concentration can be controlled by the volume fog system, or directly by the material.<br>可通过体积雾系统控制浓度，也可直接通过材质控制浓度。

* Because the volume fog system is used, the volume of fog can be adjusted for the visible distance.<br>因为使用的是体积雾系统，所以可视距离可由体积雾调整。

* There is no classification chart, and the shape of the cloud is not good-looking.<br>没有分型图，云的形状不好看。


#### Blueprint VolumemetricClouds/基于蓝图的VolumetricClouds

This is a volume cloud based on Shader, developed from a big Russian.<br>这是基于Shader的体积云，开发自一位俄罗斯大佬。

##### Feature/特性

* Look closely at the noise.<br>靠近看有噪点。
> noise has been eliminated, but now the cloud has a harder border after looking closer, please download the original version in related link 1.<br>已去除噪点，但现在靠近看之后云会有比较硬的边界，原版请在相关链接1中下载。

* Not affected by high fog.<br>不受高度雾影响。

* Very beautiful.<br>很漂亮。


### How to use it in your project?/如何在你的项目运用它们？ 

You can use one of XinixCloudBP or VolumemetricClouds or use them together.<br>你可以使用XinixCloudBP或VolumetricClouds其中之一，或者一起使用。

Developed with Unreal Engine 4.24, there is no guarantee that it will be available on other engine versions.<br>使用虚幻引擎4.24版本进行开发，故不能保证在其他引擎版本上一定可用。


#### Using Blueprint XinixCloudBP

1. Migrate XinixClouds / XinixCloudBP in UE4 to your project.<br>在UE4中移植XinixClouds/XinixCloudBP到你的项目里。

2. Place XinixCloudBP on the map.<br>在地图上放置高度雾（ExponentialHeightFog）。

3. Deflect the volume fog (Volgmetric Fog) of this height fog.<br>勾选该高度雾的体积雾（Volumetric Fog）。

4. Increase the visible distance (line of sight) of the volume fog, you can adjust it to 300000.0 to see the effect.<br>调高体积雾的可视距离（View Distance），可以调到300000.0看下效果。


#### Using Blueprint VolumemetricClouds

1. Grafting VolumetricClouds / VolumetricClouds.<br>移植VolumetricClouds/VolumetricClouds。

2. Place VolumetricClouds on the map.<br>在地图上放置VolumetricClouds。

### TODO

* Add fractal processing to the material of XinixCloudBP<br>为XinixCloudBP的材质添加分形处理

***

### License/许可

This system complies with the [![MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE) agreement.<br>本系统遵循 [![MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE) 协议分发。

***

### Related Links/相关链接

1. [VolumetricClouds developer’s Website](https://www.artstation.com/artwork/GXnrvV)

2. [Dry ice making tutorial](https://zhuanlan.zhihu.com/p/107016039)
