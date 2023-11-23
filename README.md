# Face Mask Detection using YOLO V6



## Overview

This project utilizes YOLOv6, a state-of-the-art object detection model, to detect faces and identify whether individuals are wearing face masks. The primary goal is to contribute to public health by automating the monitoring of face mask compliance in various environments.

## Requirements

- Python 3.x
- PyTorch
- OpenCV
- YOLOv6 (Follow installation instructions [here](https://github.com/ultralytics/yolov6))

## Installation

1. Clone the YOLOv6 repository:

    ```bash
    git clone https://github.com/ultralytics/yolov6.git
    ```

2. Navigate to the YOLOv6 directory:

    ```bash
    cd yolov6
    ```

3. Install the required dependencies:

    ```bash
    pip install -U -r requirements.txt
    ```

4.  Train the model, and have the weights privy to the model.
   
5.  Customize the YOLOv6 configuration based on your needs.

## Dataset

For training the face mask detection model, I used a dataset containing images annotated with bounding boxes around faces and labeled with mask/without_mask. I created my own dataset, using google images. 

## The Jupyter notebook

The Jupyter notebook associated with this repository displays the results of the model on test images.
