# 🐶 Dog Face Detection using YOLOv8

## 📌 Project Overview
This repository contains a deep learning project focused on accurate dog face detection in images and videos. By leveraging the state-of-the-art YOLOv8 object detection architecture, we've trained a model specifically for identifying dog faces with high precision and recall.

## 🔍 Key Features
- Real-time dog face detection
- High accuracy metrics (mAP50 92.71%, 88.5% recall)
- Works on various dog breeds and poses
- Optimized for reasonable inference speed

## 🧠 Model Performance
Our fine-tuned YOLOv8 model achieved the following metrics:

| Metric | Value |
|--------|-------|
| Precision (B) | 89.32% |
| Recall (B) | 88.46% |
| mAP50 (B) | 92.71% |
| mAP50-95 (B) | 57.88% |
| Fitness | 61.36% |

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
4. Validation on a separate test set

