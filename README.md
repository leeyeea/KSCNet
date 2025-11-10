#### KSCNet
An implementation of KSCNet (Exploring KAN and State Space Model for Small Object Detection from UAV Imagery )

#### KSCNet:Exploring KAN and State Space Model Collaboration Network for Small Object Detection from UAV Imagery.  [Expert System with Applications 2025]

##### Main architecture of KSCNet
<img width="600" height="600" alt="main" src="https://github.com/user-attachments/assets/fefaabe9-5ae2-43c2-ac78-2f3a2c28f323" />

##### Qualitative visualization comparisons on the SIMD dataset of KSCNet and baseline model
<img width="600" height="600" alt="coms1" src="https://github.com/user-attachments/assets/dd04a62f-d182-4dec-a3bf-f3e33a6bbdc6" />

#####  Visualization comparison of Heatmap by Grad-CAM between baseline and KSCNet
<img width="600" height="600" alt="coms2" src="https://github.com/user-attachments/assets/d12851b5-b07a-458a-bcae-e517786404e5" />


##### Visualization of detection performance of KSCNet with advanced realtime YOLO detectors YOLO10s, YOLO11s and YOLOv12s on the VisDrone dataset
<img width="600" height="600" alt="coms3" src="https://github.com/user-attachments/assets/24df6260-c016-44da-8f85-63b39553029c" />


##### Welcome have citations of KSCNet
> @article{LI2025130240,
title = {KSCNet:Exploring KAN and State Space Model Collaboration Network for Small Object Detection from UAV Imagery},
journal = {Expert Systems with Applications},
pages = {130240},
year = {2025},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2025.130240},
url = {https://www.sciencedirect.com/science/article/pii/S0957417425038552},
author = {Yi Li and Huiying Xu and Yiming Sun and Pengfei Zhu and Lingling Xu and Xinzhong Zhu},
keywords = {Unmanned Aerial Vehicle, Small Object Detection, Kolmogorov–Arnold Networks, State Space Model},
abstract = {Detecting small objects in aerial images taken by unmanned aerial vehicles (UAVs) has become a crucial research challenge in the field of computer vision. This challenge is attributable to the following primary factors: the small size of the targets, the complexity of the background and the inadequate feature fusion, which makes small targets more susceptible to limited effective information and inferior detection performance. To address this issues, we propose a collaboration network that integrates Kolmogorov–Arnold Networks (KAN) and State Space Model (SSM) to improve the small target detection performance from UAV imagery. Specifically, we employ the KAN inserted into original YOLO11 architecture as primary backbone for feature extraction, which is sufficient to decompose complex high-dimensional data into simple one-dimensional function combinations so as to efficiently explore features with strong expressive power. We design Semantic Aggregation Network (SAN) to perform highly-effective multiscale feature fusion of global patterns. The SSM module plays a crucial role in SAN, which has been demonstrated to exhibit a superior capacity to adapt to a variety of input data types through its distinctive scanning strategy and dynamic weighting mechanism, especially for the complicated UAV images. An efficient Depthwise Channel Attention (DCA) is developed to reduce the aliasing effects generated from fused feature via lightweight channel dimension refinement. Extensive experiments on the public UAV datasets have been conducted to validate the effectiveness of KSCNet. Concretely, KSCNet performs 0.844 mAP@50 and 0.691 mAP@50:95 on the SIMD dataset, achieving 1.69% and 2.22% accuracy improvement compared with baseline. Moreover, KSCNet also accomplishes 4.82% and 5.11% accuracy increase on the VisDrone validation set and 4.43% and 6.16% boost on the VisDrone test set at mAP@50 and mAP@50:95 respectively, indicating that the KSCNet demonstrates excellent performance in the UAV small object detection task, providing substantial technical support for applications in related domains.}
}
