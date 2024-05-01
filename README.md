Action Is Important: Action Augmentation Video Moment Retrieval
=====
[Jiayu Song](https://cn.linkedin.com/in/jiayusong1999)

## Introduction
- Soft Contrastive Bilinear Video Moement Retrieval
- Action Augmentation Video Moment Retrieval


## Data
运行 prepare_data.sh 文件下载Charades和ActivityNet Captions数据集。

## evaluate pre-trained models
为方便验证模型的有效性，预训练模型地址：[Baidu NetDisk](https://pan.baidu.com/s/1ydqOZ6qer6MdR14x6BwdDw) , 提取码：uky2 

将模型下载后放在pretained_models文件下。

- **Ablation Study & Hyperparameter Analysis** 
- 消融实验，超参数敏感性分析实验 各模型，训练过程，测试结果均在其中，以.txt和.png文件存储。


## Multimodal Compact Bilinear Fusion in VMR
针对传统特征融合过程计算效率低，特征存储成本高且融合深度不足，从而使检索准确率下降这一问题，引入了双线性特征融合算法(Multimodal Compact Bilnear Fusion)来降低特征存储成本和提高特征融合深度，为提升视频检索准确性提供基础。

## Code
The framework of AGVMR is based on [LGI](https://github.com/JonghwanMun/LGI4temporalgrounding). On the basic of it, add MCB block, action augmentation block, soft contrastive Loss(for SCBVMR) and mean square loss(for agvmr) to improve the accuary of vmr. Many thanks for their open source and we have cited their paper in our work. 

## Train


## Test
