# Object Detection for Visually Impaired People

## Introduction

Vision impairment is one of the top disabilities globally, affecting millions of people worldwide. Visually impaired individuals face numerous challenges in their daily lives, including difficulty identifying objects around them and navigating their surroundings. This project aims to develop an object detection application to assist visually impaired people in navigating their surroundings and identifying objects of interest.

### Creating the Detection Model

1. Run yolo_algo.ipynb to create the YOLO object detection model. This will generate a model.h5 file.
2. The model only needs to be created once. The generated model.h5 can be reused.

### Running Object Detection

1. Run main.ipynb to run real-time object detection using the created model.h5.
2. main.ipynb needs to be executed each time you want to detect objects.
3. Connect a camera and point it at objects.
4. Detected objects and information will be conveyed through audio.

### Requirements

The following libraries are required to run the application:

| Library | Version |
|---|---|
| Python | 3.9.17 |
| NumPy | 1.24.3 |
| Keras | 2.13.1 |
| Keras-Preprocessing | 1.1.2 |
| opencv-python | 4.8.0.76 |
| pyttsx3 | 2.90 |
| yolov3-416 weights | [Drive link](https://drive.google.com/file/d/1sRdGUSyfGW-tz-FaJ0-ufCjzVQF7sleX/view?usp=sharing) |

### Installation

To install the required libraries and weights, follow these steps:

1. Install the libraries using the following commands:

```bash
pip install python==3.9.17
pip install numpy==1.24.3
pip install keras==2.13.1
pip install keras-preprocessing==1.1.2
pip install opencv-python==4.8.0.76
pip install pyttsx3==2.90
```
2. Download the yolov3-416 weights from the provided Drive link and place the downloaded file in the appropriate location within your project directory.

