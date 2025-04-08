# 🐶 Dog Face Detection using YOLOv8

## 📌 Project Overview

This repository contains a deep learning project focused on accurate dog face detection in images and videos. By leveraging the state-of-the-art YOLOv8 object detection architecture, we've trained a model specifically for identifying dog faces with high precision and recall.

## 🔍 Key Features

- Real-time dog face detection
- High accuracy metrics (mAP50 92.71%, 88.5% recall)
- Works on various dog breeds and poses
- Optimized for reasonable inference speed

## Metrics

![confusion_matrix](https://github.com/user-attachments/assets/6efc72a7-8bc0-4957-883d-20ad2a93ee12)
![F1_curve](https://github.com/user-attachments/assets/6c0ebcef-25c0-4a41-bb0d-8550543ff873)
![labels](https://github.com/user-attachments/assets/1b85af80-baf7-4753-9e89-8ccb9644d7ea)

## Samples

![val_batch1_pred](https://github.com/user-attachments/assets/c7cddc12-f64f-4c2c-ad9b-463f557e2039)
![val_batch0_pred](https://github.com/user-attachments/assets/f81d4598-0248-4dd8-a8b0-665f46e964ab)


## 🧠 Model Performance

Our fine-tuned YOLOv8 model achieved the following metrics:

| Metric        | Value  |
| ------------- | ------ |
| Precision (B) | 90.19% |
| Recall (B)    | 88.6%  |
| mAP50 (B)     | 94.2%  |
| mAP50-95 (B)  | 57.88% |
| Fitness       | 60.83% |

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- Ultralytics YOLOv8
- OpenCV

### Installation

```bash
# Clone this repository
git clone https://github.com/yashkc2025/dog_face_detection.git
cd dog-face-detection

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

## 🐾 Applications

Dog face detection can be utilized in various domains:

- Pet monitoring systems
- Veterinary health applications
- Animal behavior analysis
- Pet photography automation

## 📚 Model Training

The model was trained using the following approach:

1. Dataset preparation with dog face annotations
2. Transfer learning using a pre-trained YOLOv8 model
3. Validation on a separate test set
