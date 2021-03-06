# segentation

## Abstract

Implement classic segmentation models with pytorch.

We try to segment the roads in Cityscapes, which is a fundamental task in auo-driving.

Plus, we test the models in both sunny and foggy envirments.

We compared the following models:
* bisenet
* icnet
* fcn8/16/32
* linknet
* pspnet
* unet
* segnet

And BiSeNet is the best of them.

Please refer to out report to more details!

## Files
* \net: network models
* main.py: main program 
* \demo: demo images
* \resdemo: the segmentation result of the demo images
* segmetation.pdf: report

## Demo

![sunny](https://github.com/TrueNobility303/pytorch-segentation/tree/master/results/sunny_cmp_img.png)

<center> Sunny Cityscapes </center>

![foggy](https://github.com/TrueNobility303/pytorch-segentation/tree/master/results/foggy_cmp_img.png)

<center> Foggy Cityscapes </center>

## 摘要
利用pytorch实现经典语义分割网络，基于卷积神经网络，探究了使用卷积神经网络进行语义分割
并且探究了图片级联模块、特征金字塔模块、跳层连接等结构的作用
在cityscapes数据集上实现道路分割,在晴天和浓雾天气下都有不俗的表现
在晴天数据集上训练，并跨域至雾天数据集
实现了以下模型，
* bisenet
* icnet
* fcn8/16/32
* linknet
* pspnet
* unet
* segnet

## 文件说明
* net 定义分割网络结构
* main.py 主程序
* demo 示例用图
* resdemo 分割结果
* segmetation.pdf 报告和代码说明

## 示例

![sunny](https://github.com/TrueNobility303/pytorch-segentation/tree/master/results/sunny_cmp_img.png)

<center> 晴天训练结果 </center>

![foggy](https://github.com/TrueNobility303/pytorch-segentation/tree/master/results/foggy_cmp_img.png)

<center> 跨域雾天结果</center>
