# libtorchYoloV3
First of all, thanks for https://github.com/walktree walktree's great Job.

This repo was modified based on the walktree's job, i've rewritten it with Libtorch v1.6.0 stable version(the lastest one 13th August 2020)

A Libtorch implementation of the YOLO v3 object detection algorithm, written with pure C++. It's fast, easy to be integrated to your production, and CPU and GPU are both supported. Enjoy ~


## Requirements
1. LibTorch v1.6.0
2. Cpu
3. OpenCV (4.3.0)

IDE tool
Visual studio 2017 

## Running the detector

The first thing you need to do is to get the weights file for v3:

```
cd models
wget https://pjreddie.com/media/files/yolov3.weights 
```

On Single image:
```
./{your test image path}/imgs/person.jpg
```

As I tested, it will take 2700 ms on Cpu,please run inference job more than once, and calculate the average cost.
