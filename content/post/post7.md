+++
date = "2023-04-15"
short_text = "改进yolov8的缺陷检测"
title = "余凯"
[[authors]]
    name = "member1"
    is_member = true
    link = "/member1"
+++



# 改进yolov8的缺陷检测

## 摘要
为提高钢材表面缺陷检测效率，提出一种改进的yolov8网络结构，首先替换主干特征提取网络为C3_faster，使用partial_conv结合C3，减少模型计算量的同时也保证网络的学习能力。颈部特征融合网络嵌入无参注意力，进一步加强网络特征提取的能力，并且改进上采样算子替换原来网络的 最近邻上采样。最后使用wise-iou进一步提升网络性能。