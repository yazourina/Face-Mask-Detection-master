# Face-Mask-Detection-master

# Face Mask Detection API

This is a Flask-based REST API that performs face mask detection using a fine-tuned ResNet18 model. It accepts an image via POST request and returns a classification result: either **with_mask** or **without_mask**.

## 🚀 Features

- Uses PyTorch and a modified ResNet18 architecture
- Classifies images into "with_mask" or "without_mask"
- Flask API for easy deployment and integration
- Compatible with CPU and GPU

---

## 🧠 Model

- Architecture: [ResNet18]
- Pre-trained on ImageNet
- Final FC layer replaced to output 2 classes
- Trained weights loaded from `Face-Mask-Detection-master.pth`
- Model link is on my Kaggle accout (currently having problems uploading)

---

## 🛠 Installation

### Requirements

- Python 3.7+
- `torch`, `torchvision`
- `flask`, `Pillow`

### Install Dependencies

```bash
pip install torch torchvision flask pillow
