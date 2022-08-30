# CVproject
抖音项目源码分享

## 目标检测课程大纲：第一阶段

### 课程大纲: **“理论+实战”，从0到1带您全方位入门目标检测**

### 一 理论精讲：通用目标检测理论知识

#### 1. 理论精讲：目标检测研究背景

- 目标检测的定义

- 目标检测相关任务的内在联系

- 目标检测的意义

#### 2. 理论精讲：目标检测算法整体发展脉络

- 第一阶段：传统机器学习算法

- 第二阶段：深度学习方法

#### 3. 理论精讲：目标检测常用数据集

- 通用物体检测常用数据集

- 人脸检测常用数据集

- 行人检测常用数据集

#### 4. 理论精讲：目标检测评价指标

##### 4.1 检测精度评价指标

- 召回率  

- 平均精度值  

- 平均对数漏检  

##### 4.2 检测速度评价指标

- 前传耗时  

- 每秒帧数  

- 浮点运算量

### **二    理论精讲：传统目标检测算法**

- 理论精讲：传统目标检测算法的原理

- 理论精讲：传统目标检测算法实现步骤

- 理论精讲：Viola Jones检测器

- 理论精讲：HOG检测器

- 理论精讲：基于可变形部件的模型（DPM）

### **三    理论精讲：深度学习目标检测算法**

#### 1. 理论精讲：基于锚框的目标检测算法

##### 1.1 理论精讲：多阶段目标检测算法概述

- 发展脉络：

R-CNN ——> Fast R-CNN ——>Faster R-CNN——>FPN——>Mask R-CNN

- R-CNN原理概述

- Fast R-CNN原理概述

- Faster R-CNN原理概述

- 实战精讲：Faster R-CNN网络结构详解以及代码解读

- R-CNN系列算法总结

##### 1.2 理论精讲：单阶段目标检测算法概述

- SSD系列目标检测算法发展脉络

- 实战精讲：SSD目标检测算法网络结构详解以及代码解读

- RetinaNet目标检测算法原理概述

- 实战精讲：RetinaNet目标检测算法网络结构详解以及代码解读

- EfficientDet目标检测算法原理概述

- 实战精讲：EfficientDet目标检测算法网络结构详解以及代码解读

- YOLO系列目标检测算法发展脉络 

- 实战精讲：YOLOv5目标检测算法网络结构详解以及代码解读

#### 2. 理论精讲：无需锚框目标检测算法

##### 2.1 理论精讲：关键点法原理以及实现步骤

##### 2.2 CornerNet

- 原理概述

- 网络结构

##### 2.3 理论精讲：中心域法原理以及实现步骤

##### 2.4 FCOS

- 原理概述

- 网络结构                            

#### 3. 理论精讲：基于Transformer架构的目标检测（DETR）

##### 3.1 理论精讲：Transformer整体架构

- 认识Transformer架构

- 输入部分的实现

- 编码器部分实现

- 解码器部分实现
- 输出部分实现

##### 3.2 理论精讲：DETR系列目标检测算法研究概况

##### 3.3 理论精讲：DETR的实现原理

- CNN特征提取

- Transformers的encoding-to-endcoding进行信息的融合

- FFN预测class和box

- 实战精讲：DETR网络结构详解以及代码解读
