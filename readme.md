# FaceForensic

XDU-SCE 信息与内容安全大作业 虚假人脸检测实验

A simple fake face forensic classifier implemented by MesoNet and ResNet-18

给定一个人脸数据集，其中包含1999张真实人脸，1999张虚假人脸。将其中500张真实人脸和500张虚假人脸作为训练集，其余作为测试集。

根据给定数据集训练训练一个虚假人脸检测器，该检测器本质就是一个二分类器。要求利用Pytorch框架任意设计一种神经网络模型进行分类，分类准确率越高越好(分类准确率和得分不相关)。