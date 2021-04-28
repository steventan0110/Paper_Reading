# CV - Classification & Segmentation
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Rich feature hierarchies for accurate object detection and semantic segmentation Tech report (v5)](https://arxiv.org/pdf/1311.2524.pdf)|Paper|IEEE|R-CNN paper, proposed selective search to find 2000 regions of interests then compute CNN features and feed into SVM classifier. 4 bounding box values are also predicted to adjust the original bbox.|
|[Fast-R-CNN](https://arxiv.org/abs/1504.08083)|Paper|ICCV|Using deep learning for selective search in R-CNN. feed input to CNN and generate conv feature map. Then RoI are identified and pooled. The RoI feature is used for both prediction task and regressor task (for bbox adjustment)|
|[Faster R-CNN](https://arxiv.org/pdf/1506.01497.pdf)|Paper|IEEE|Eliminate selective search step with object detection algorithm. A region proposal network is introduced and used to propose RoI for pooling. Can be used for real-time detection.|
|[You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/pdf/1506.02640.pdf)|Ppaer|CVPR|SxS grids each with m by m boxes. The network predict a class probability along with offset value to adjust bbox.|

[Back to index](../README.md)