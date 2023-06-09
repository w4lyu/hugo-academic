+++
date = "2023-04-13"
short_text = "Jun. 2023.基于定位蒸馏的密集目标检测"
title = "廖龙杰"
[[authors]]
    name = "member1"
    is_member = true
    link = "/member1"
[[authors]]
    name = "member2"
    is_member = true
    link = "/member2"
+++



# 基于定位蒸馏的密集目标检测

## 摘要
知识蒸馏（KD）在目标检测中学习压缩模型方面表现出强大的能力。以往的目标检测KD方法主要集中在模仿模型区域内的深度特征上，而不是在分类中模拟对数，因为在提取定位信息时效率低下。通过对定位的知识蒸馏过程进行重新构建，提出了一种新的定位蒸馏（LD）方法，可以有效地将定位知识从教师模型转移到学生模型。此外，还引入了有价值的定位区域的概念，可以帮助有选择地提取某个区域的语义和定位知识。通过结合这两个新组件，首次展示了对数模拟可以优于特征模仿，并且定位知识蒸馏比语义知识更重要和更有效地提取目标检测器的信息。该蒸馏方案既简单又有效，并且可以轻松应用于不同的密集目标检测器中。