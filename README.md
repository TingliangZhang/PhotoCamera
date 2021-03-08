# PhotoCamera
能拍照的相框



## STEEP分析

社会：解决老年人不方便用手机拍照问题，黑白墨水屏有黑白胶片机时代怀旧感，减少操作步骤优化交互流程，墨水屏无需充电

技术：墨水屏逐渐普及廉价，之后可以搞彩色墨水屏。

经济：模块化设计，有效节约资源，降低套件造价

环境：耗电量低，不送Type-C充电器，环保

政治：老龄化社会，需求多



## 硬件方案

电纸屏+树莓派+树莓派摄像头

电纸屏选型：单独驱动板，双色，三色甚至7色的屏

[e-Paper Driver HAT](https://www.waveshare.net/wiki/E-Paper_Driver_HAT)

[5.83inch e-Paper HAT](https://www.waveshare.net/wiki/5.83inch_e-Paper_HAT)

[5.83inch e-Paper HAT (B)](https://www.waveshare.net/wiki/5.83inch_e-Paper_HAT_(B))

[5.83inch e-Paper HAT (C)](https://www.waveshare.net/wiki/5.83inch_e-Paper_HAT_(C))

[5.65inch e-Paper Module (F)](https://www.waveshare.net/wiki/5.65inch_e-Paper_Module_(F))

决定用树莓派zero+PowerModule+[5.83inch e-Paper HAT](https://www.waveshare.net/wiki/5.83inch_e-Paper_HAT)



## 软件方案

ArtLine生成线稿图，之后转成BMP

其实直接用OpenCV转成黑白BMP图像也可