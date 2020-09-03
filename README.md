# IMD
Intelligent Mask Detection via Deep Learning Algorithms

## System Architecture
<div align="center">

![architecture1](https://github.com/94JuHo/IMD/asset/img/system_architecture.jpg)  

</div>
  
## Purpose
We thought about how to detect people not wearing masks in various place.  
So, we would like to propose an efficient mask detection system that can also be used on embedded machines with limited resources.  
  
## Envirments
H/W : CPU(i5-9400F), RAM(16G), GPU(RTX2070super)  
OS : Ubuntu 18.04  
IDE : Pycharm  
Language : Python 3.7  
Libary : Opencv, numpy, Mxnet etc..  

#### Demonstration Video  
[![Video Label](http://img.youtube.com/vi/TxW3jxQz3zI/0.jpg)](https://youtu.be/TxW3jxQz3zI)

### To-Do
- [ x ] Face detection algorithm
- [ x ] Mask detection is performed via face detection algorithm
- [  ] Mask detection via Lightweight ReXNet algorithm
- [  ] Fusing face detection and mask detection

#### Reference
- https://github.com/deepinsight/insightface/tree/master/RetinaFace
- https://github.com/clovaai/rexnet