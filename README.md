# YOLO Car Object Detection

<p align="justify">Enter the realm of cutting-edge computer vision with AutoVision, a groundbreaking project that employs YOLO (You Only Look Once) to revolutionize car object detection. With unparalleled speed and accuracy, AutoVision is designed to identify and locate vehicles within images and videos in real-time, transcending traditional methods.</p>

dataset - https://www.kaggle.com/datasets/sshikamaru/car-object-detection

---

### Installation

First you have to install python or anaconda in your system.

1. Create virtual environment
```bash
  # for python
  python -m venv yolo
  
  # for anaconda
  conda create -n yolo
```

2. Activate virtual environment
```bash
  # for python
  ./yolo/Scripts/activate
  
  # for anaconda
  conda activate yolo
```

3. Install ipykernel
```bash
  pip install ipykernel
```

4. Create kernel for yolo
```bash
  python -m ipykernel install --user --name=yolov5
```