# XinRepo

# DLN+YOLOV5

## 简介

此项目旨在复现论文《Deep Enhancement-Object Features Fusion for Low-light Object Detection》

- 论文链接: [https://dl.acm.org/doi/10.1145/3551626.3564947]

## ExDark数据集

您可以通过以下链接下载所需的数据集：

- 数据集下载链接:[https://aistudio.baidu.com/datasetdetail/129450]
- 原地址为：[https://github.com/cs-chan/Exclusively-Dark-Image-Dataset]
- 数据集简介：[https://zhuanlan.zhihu.com/p/472237704]
请确保下载并解压数据集到项目的指定目录以便正常运行程序。

## 预训练权重

DLN模型，epoch=500，预训练权重文件已包含在代码仓库中，您可以在以下位置找到它们：

- `DLN_yolov5/DLN_master/models`

yolov5预训练权重请到官网下载。

## 使用说明

若要下载并使用本程序进行训练，您需要对代码进行一些改动。具体改动位置如下：

- `exdark.py`

更改数据集配置文件下面数据集的具体路径，以确保训练过程的顺利进行。



## 联系方式

如有任何问题或建议，请随时与我联系。
- 我的邮箱: [sunyx3197@163.com]

