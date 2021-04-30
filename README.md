# segentation

## 摘要
利用pytorch实现经典语义分割网络，基于卷积神经网络，探究了使用卷积神经网络进行语义分割
并且探究了图片级联模块、特征金字塔模块、跳层连接等结构的作用
在cityscapes数据集上实现道路分割,在晴天和浓雾天气下都有不俗的表现
实现了以下模型，
* icnet
* fcn8/16/32
* linknet
* pspnet
* unet
* segnet

## 示例

![] (https://github.com/TrueNobility303/pytorch-segentation/blob/master/demo/foggy1.png)
<center> 原图 </center>
![] (https://github.com/TrueNobility303/pytorch-segentation/blob/master/resdemo/fcn8/res_foggy1.png)
<center> 分割结果 </center>
