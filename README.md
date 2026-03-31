# Face Mask Detection 

A real-time face mask detection system using deep learning and computer vision techniques. This project detects whether a person is wearing a face mask or not using a webcam or image input.

---

##  Project Overview

This project was developed to explore the application of Convolutional Neural Networks (CNN) in real-world scenarios. The model is trained to classify faces into two categories:
- **With Mask**
- **Without Mask**

---

##  Technologies Used

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib
- MobileNetV2 (Transfer Learning)

---

##  Dataset

The dataset consists of images of people with and without face masks. It is divided into two categories:
- `with_mask`
- `without_mask`

---

##  How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/ashishmerit/CV_Project_mask_detection.git
   cd CV_Project_mask_detection
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model**
   ```bash
   python train_mask_detector.py
   ```

4. **Run real-time detection**
   ```bash
   python detect_mask_video.py
   ```

---

## 📊 Results

The model achieves high accuracy in detecting face masks in both images and real-time video streams.

---

##  Credits

This project is based on the original work by **Balaji Srinivas**:
The dataset was taken from

https://github.com/balajisrinivas/Face-Mask-Detection/tree/master/dataset

---
