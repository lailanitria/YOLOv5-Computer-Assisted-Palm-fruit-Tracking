# 🌴 Oil Palm Tree Detection using YOLOv5

This project implements a custom object detection model using **YOLOv5s** to identify oil palm trees from aerial or field images. The training process involves customizing the YOLOv5 architecture and utilizing a dataset from Roboflow.

---

## 📁 Dataset

- **Source**: Roboflow project `pokok-kelapa-sawit`
- **Workspace**: `zarif-technologies`
- **Version**: 6
- **Format**: YOLOv5-compatible with `data.yaml`

Dataset was automatically downloaded and preprocessed using Roboflow API.

---

## ⚙️ Setup

Clone the YOLOv5 repo and install dependencies:

```bash
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
pip install -U imageio roboflow
