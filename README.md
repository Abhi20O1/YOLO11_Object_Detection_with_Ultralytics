# YOLO11 Object Detection with Ultralytics

A notebook-based object-detection experiment using YOLO11 and the Ultralytics framework to locate common objects in images.

## Features

- Uses a pretrained YOLO11 model
- Detects the standard COCO object categories supported by the model
- Visualizes detections with OpenCV and Matplotlib
- Includes an example output image in `download.png`

## Setup

```bash
pip install ultralytics opencv-python matplotlib numpy jupyter
jupyter notebook
```

Open `Object_Detection.ipynb`, update the input image path if needed, and run the cells in order. Model weights are downloaded by Ultralytics when requested.

## Responsible use

Detection results vary with image quality, viewpoint, and domain shift. Validate the model on representative data before using it in an application.
