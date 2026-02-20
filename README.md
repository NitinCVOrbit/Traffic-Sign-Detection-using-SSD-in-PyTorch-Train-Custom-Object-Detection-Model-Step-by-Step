# 🚦 Traffic Sign Detection using SSD300-VGG16 (PyTorch)

This project implements **Traffic Sign Detection using SSD300 with VGG16 backbone** in PyTorch.  
The model is trained using a custom dataset exported from Roboflow and detects **28 traffic sign classes** with bounding boxes and labels.

---

## 🚀 Features

- Pretrained SSD300-VGG16 (Transfer Learning)
- Custom PyTorch Dataset (YOLO → PyTorch conversion)
- Automatic dataset cleaning
- Custom classification head (28 classes)
- GPU training support
- Training loss visualization
- Inference with bounding box detection
- Model saving and loading

---

## 🧠 Model Details

- Model: SSD300
- Backbone: VGG16
- Framework: PyTorch
- Classes: 28 + background
- Input Size: 640×640

---
