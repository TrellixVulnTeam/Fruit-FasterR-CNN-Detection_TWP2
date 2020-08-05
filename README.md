# Fruit-FasterR-CNN-Detection
Using Pytorch to create multiple Faster R-CNN models to detect images of fruit.

## Modified Faster R-CNN model
I modified PyTorch's torchvision Faster R-CNN class to both give losses and predictions while in eval() mode to allow ease of access to calculate the training loss.
My modified torchvision repository is [HERE](https://github.com/Coldestadam/vision_)

These are the files I modified:
1. [generalized_rcnn.py](https://github.com/Coldestadam/vision_/blob/master/torchvision/models/detection/generalized_rcnn.py)
2. [roi_heads.py](https://github.com/Coldestadam/vision_/blob/master/torchvision/models/detection/roi_heads.py)
3. [rpn.py](https://github.com/Coldestadam/vision_/blob/master/torchvision/models/detection/rpn.py)

## [Samples](samples)

![img](samples/sample_9.jpg)

Please click on the link above to check 10 sample images.

## Results:
I was not able to get the best results due to lack of resources, but I was able to implement the algorithm which was my goal. Thank you for checking this out!
