# Object_Detection_using_YOLOv3
YOLO (You Only Look Once) : Real time object detection technique

- The “**You Only Look Once**,” or YOLO, family of models are a series of end-to-end deep learning models designed for fast object detection.

- The approach involves a single deep convolutional neural network (originally a version of GoogLeNet, later updated and called **DarkNet** based on **VGG**) that splits the input into a grid of cells and each cell directly predicts a bounding box and object classification.

- The result is a large number of candidate bounding boxes that are consolidated into a final prediction by a post-processing step.

- There are three main variations of the approach, **YOLOv1**, **YOLOv2**, and **YOLOv3**.

- We will use **experiencor**’s [keras-yolo3](https://github.com/experiencor/keras-yolo3) project as the basis for performing object detection with a YOLOv3 model.

[Jupyter Notebook](./Object_Detection_using_YOLOv3.ipynb)
