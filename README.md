# 项目思路

![image](https://github.com/Jangge/Image-Description/blob/main/%25E5%259B%25BE%25E7%2589%2587.png)

## 项目目标：
- ### 给定一个图像输出针对这个图像的描述
## 模型结构：
- ### 编码器+解码器结构，编码器负责处理接受的图像，解码器负责输出描述
## 编码器要做的事：
- ### 接受图像，提取特征。
- ### 输入时图像，输出是图像的特征向量
## 解码器要做的事：
- ### 接受编码器的特征向量和源序列作为输入
- ### 源序列：对衣服图像描述的标签，力图‘一群长颈鹿’
- ### 输出对这副图像的描述

## 1、准备训练数据
    1、下载数据集
    2、对数据集图片进行处理，准备编码器输入所需的图片数据
    3、从下载的文件中提取源序列，并进行处理准备词袋，作为解码器的输入
    4、打包准备好的数据集，以便训练使用
## 2、打包数据集方便训练
## 3、定义模型
## 4、定义训练方法
## 5、验证模型


### 项目完全参考 https://github.com/yunjey/pytorch-tutorial.git
