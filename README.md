# Faster RCNN

Extract from the paper "Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks"
<https://arxiv.org/pdf/1506.01497.pdf>
---
> Our object detection system, called Faster R-CNN, is composed of two modules. 
> **The first module** is a deep fully convolutional network that proposes regions, 
>> RPN (Region Proposal Networks)
>> It takes an image (**of any size**) as input and outputs a set of rectangular object proposals, each with an objectness score. In this experiments, investigates the Zeiler and Fergus model (ZF), which has 5 shareable convolutional layers and the Simonyan and Zisserman model (VGG-16), which has 13 shareable convolutional layers. To generate region proposals, it slides a mall network over the convolutional feature map output by the last shared convolutional layer.  

> and **the second module** is the Fast R-CNN detector that uses the proposed regions.
> The entire system is a single, unified network for object detection.

---
