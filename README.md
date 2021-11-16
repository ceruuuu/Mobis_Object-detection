# SSD-based Object Detection in PyTorch

서강대학교 현대모비스 SW 프로그램에서 진행한 인공지능 프로젝트입니다.
Jetson nano를 이용해 pre-trained network를 fine tuning시켜 차량 및 신호등 인식을 구현하였습니다.


https://www.youtube.com/watch?v=jYsIBuAgdao


This repo implements [SSD (Single Shot MultiBox Detector)](https://arxiv.org/abs/1512.02325) in PyTorch for object detection, using MobileNet backbones.  It also has out-of-box support for retraining on Google Open Images dataset.  

> For documentation, please refer to Object Detection portion of the **[Hello AI World](https://github.com/dusty-nv/jetson-inference/tree/dev#training)** tutorial:
> [Re-training SSD-Mobilenet](https://github.com/dusty-nv/jetson-inference/blob/dev/docs/pytorch-ssd.md)

Thanks to @qfgaohao for the upstream implementation from:  [https://github.com/qfgaohao/pytorch-ssd](https://github.com/qfgaohao/pytorch-ssd)

