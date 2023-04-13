+++
abstract = "Defect detection is to locate and classify the possible defects in an image, which plays a key role in the quality inspection link in the manufacturing process of industrial products. Defects in industrial products are generally very small and extremely uneven in scale, resulting in poor detection results. Therefore, we propose an efficient scale-aware network (ES-Net) to improve the effect of defect detection. By addressing the information loss of tiny targets and the mismatch between the receptive field of detection head and the scale of targets, ES-Net improves the overall defect detection effect, especially for tiny defects. Considering that existing works directly use an integrated feature to enhance features at all levels, it may cause confusion in the direction of network optimization. Therefore, we propose the aggregated feature guidance module (AFGM), which first performs efficient cascading fusion of multi-level features to filter cross-layer conflicts. Then the split and aggregation enhancement (SAE) module is designed to further optimize the integrated feature map, and the result is used to guide the shallow features. Moreover, we also introduce the multi-receptive field fusion (MFF) module to generate multi-receptive field information to supplement the shallow features after dimensionality reduction. The efficient stair pyramid (ESP) is a further improvement of feature pyramid network (FPN)-based network. In particular, we propose the dynamic scale-aware head (DSH) in shallow detection layer, which can adaptively select the best detection receptive field according to different scales of targets, thereby improving the detection performance of tiny targets. Extensive experimental results on Aliyun Tianchi fabric dataset (76.2% mAP), NEU-DET (79.1% mAP), and printed circuit board (PCB) defect dataset of Peking University (97.5% mAP) demonstrate the proposed ES-Net achieves competitive results compared to the state-of-the-art (SOTA) methods. Moreover, the high efficiency of ES-Net makes it more applicable in scenarios with high real-time requirements."
date = "2022-04-20"
image = ""
image_preview = ""
publication = "IEEE Transactions on Instrumentation and Measurement"
title = "ES-Net: Efficient Scale-Aware Network for Tiny Defect Detection"
url_pdf = "https://ieeexplore.ieee.org/abstract/document/9760388"

[[authors]]
    name = "Xuyi Yu"
[[authors]]
    name = "Wentao Lyu"

[[authors]]
    name = "Di Zhou"

[[authors]]
    name = "Chengqun Wang"

[[authors]]
    name = "Weiqiang Xu"

+++
