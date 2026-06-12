# Object Detection using TensorFlow

## Overview
This project demonstrates the implementation of an Object Detection system using TensorFlow's Object Detection API. It utilizes the pre-trained SSD Inception V2 model trained on the COCO dataset to identify and classify multiple objects within images. The detected objects are highlighted with bounding boxes, labels, and confidence scores.

## Features
- Detects multiple objects in an image.
- Uses TensorFlow's Object Detection API.
- Employs the SSD Inception V2 pre-trained model.
- Supports object classification based on the COCO dataset.
- Visualizes detection results with bounding boxes and labels.
- Processes test images automatically from a specified directory.

## Technologies Used
- Python
- TensorFlow
- TensorFlow Object Detection API
- NumPy
- Pillow (PIL)
- Matplotlib
- Jupyter Notebook

## Project Structure
```
Object-Detection-TensorFlow/
│
├── Final_0DAPI.ipynb              # Main notebook containing the implementation
├── Object_detection_tensorflow.py # Python script version of the project
├── requirements.txt               # Required dependencies
├── README.md                      # Project documentation
└── test_images/                   # Sample images for testing
```

## How It Works
1. Load the pre-trained SSD Inception V2 model.
2. Import the COCO label map for object categories.
3. Read input images from the test image directory.
4. Convert images into tensors compatible with TensorFlow.
5. Perform object detection using the loaded model.
6. Extract detection boxes, classes, and confidence scores.
7. Visualize the detection results on the images.

## Dataset and Model
- **Model:** SSD Inception V2
- **Framework:** TensorFlow Object Detection API
- **Dataset:** COCO (Common Objects in Context)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/object-detection-tensorflow.git
cd object-detection-tensorflow
```

2. Install the required libraries:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook Final_0DAPI.ipynb
```

## Applications
- Autonomous systems
- Smart surveillance
- Image analysis
- Retail inventory management
- Traffic monitoring
- Educational purposes for learning computer vision

## Acknowledgements
This project is based on TensorFlow's Object Detection API and uses pre-trained models trained on the COCO dataset.

## Author
**Dipak Choudhary**
