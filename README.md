# Object Detection
An advanced deep learning-based object detection system using Faster R-CNN with ResNet-50 FPN trained on the Pascal VOC 2012 dataset. The model detects and localizes multiple object categories in real-time on both images and videos.

# Project Overview
This project applies computer vision and deep learning to detect real-world objects such as people, animals, vehicles, and more. It uses the Faster R-CNN model pre-trained and fine-tuned on the Pascal VOC 2012 dataset. A user-friendly Tkinter-based GUI allows uploading of images or videos, as well as real-time detection via webcam, displaying bounding boxes and labels for detected objects.

# Technologies Used
Programming Language: Python
Libraries: PyTorch, Torchvision, OpenCV, NumPy, Tkinter
Model Architecture: Faster R-CNN with ResNet-50 FPN backbone
Dataset: Pascal VOC 2012 (20 object classes + background)
Optimization: SGD optimizer with momentum and weight decay

# Features
Detects 20 different object categories from the Pascal VOC dataset

Supports both image and video uploads for detection

Real-time webcam object detection with bounding boxes

Built-in GUI using Tkinter with start, stop, and reset functionality

Easy-to-use interface for demonstration and testing

# Future Improvements
Add support for COCO or custom datasets with more classes

Improve speed with lightweight models like YOLOv5 or YOLOv8

Deploy as a Flask web application or Streamlit app

Visualize class-wise detection confidence and add export options

Optimize video stream handling for higher FPS on CPU

# License
This project is open-source under the MIT License.
