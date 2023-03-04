## 1. Labelme 是什么？

Labelme 是一个图形界面的图像标注软件。其的设计灵感来自于 http://labelme.csail.mit.edu/ 。它是用 Python 语言编写的，图形界面使用的是 Qt（PyQt）。

## 2.Labelme 能干啥？
* 对图像进行多边形，矩形，圆形，多段线，线段，点形式的标注（可用于目标检测，图像分割，等任务）。
* 对图像进行进行 flag 形式的标注（可用于图像分类 和 清理 任务）。
* 视频标注
* 生成 VOC 格式的数据集（for semantic / instance segmentation）
* 生成 COCO 格式的数据集（for instance segmentation）

## 3.使用

在该[仓库地址](https://github.com/wkentaro/labelme)详细说明了labelme在不同环境下的安装及配置过程，大家也可以直接使用Releases中发布的最新版本，本仓库仅提供windows下的exe文件，可直接点击使用。