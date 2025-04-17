# BackgroundSubtraction-ImageProcessing
A GMM and SVM-based hybrid background subtraction system. It merges image processing and machine learning to enhance dynamic accuracy. Applicable for surveillance, object tracking, and real-time video analysis.
# Background Subtraction Based on Image Processing and Machine Learning

A hybrid background subtraction system based on **Gaussian Mixture Models (GMM)** and **Support Vector Machines (SVM)** is implemented in this project to enhance the accuracy of moving object detection in video streams. Traditional image processing and machine learning are combined for more accurate results under dynamic scenarios.
---

## Objectives

- Detect foreground objects from background accurately in real-time videos
- Minimize false positives due to shadows, flicker, and noise
- Create a modular, flexible, and lightweight computer vision pipeline

---

##  Technologies Used

- Python 3.8+
- OpenCV
- NumPy
- Scikit-learn
- scikit-image
- joblib
- Jupyter Notebook / VS Code

---

## How It Works

1. **GMM Background Subtraction**  
   Uses OpenCV's Gaussian Mixture Model to identify foreground pixels.

2. **Morphological Operations**  
   Eliminates noise and small features with erosion and dilation.

3. **Feature Extraction**
   Utilizes region-based features such as Local Binary Patterns (LBP) and shape descriptors.

4. **SVM Classification**
   Trained SVM model classifies identified regions as foreground objects or background noise.

---

##  Getting Started

###  Installation
```bash
git clone https://github.com/your-username/BackgroundSubtraction-ImageProcessing.git
cd BackgroundSubtraction-ImageProcessing
pip install -r requirements.txt
```
####  Results
Average F1-score: 0.89

Real-time performance: ~20 FPS

Improved noise and shadow removal

#### Future Improvements
Implement lightweight deep learning (e.g., MobileNet)

Deploy on edge devices (Jetson Nano, Raspberry Pi)

Implement multi-class object classification

####  License
This project is academic and research only.

####  Contributions
Pull requests are welcome! Open issues for suggestions or bugs anytime.
