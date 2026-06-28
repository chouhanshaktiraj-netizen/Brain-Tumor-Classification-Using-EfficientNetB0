# Brain Tumor Classification Using EfficientNetB0

## Project Overview

This project implements a deep learning model for automatic brain tumor classification using MRI images. The model is developed using **EfficientNetB0** with **Transfer Learning** to classify MRI scans into four categories with high accuracy.

---

## Dataset

**Brain Tumor MRI Dataset**

### Classes

* Glioma
* Meningioma
* Pituitary
* No Tumor

**Dataset Split**

* Training Images: 5600
* Testing Images: 1600

---

## Technologies Used

* Python
* TensorFlow
* Keras
* EfficientNetB0
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Model Architecture

* EfficientNetB0 (Pre-trained on ImageNet)
* Global Average Pooling Layer
* Dense Layer (512 neurons)
* Dropout (0.5)
* Dense Layer (256 neurons)
* Dropout (0.3)
* Softmax Output Layer (4 Classes)

---

## Data Preprocessing

* Image Resizing (300 × 300)
* Rotation
* Zoom
* Width Shift
* Height Shift
* Horizontal Flip
* Brightness Adjustment
* EfficientNet Preprocessing

---

## Training Configuration

* Optimizer: Adam
* Learning Rate: 0.0001
* Batch Size: 32
* Loss Function: Categorical Crossentropy
* Epochs: 30
* EarlyStopping
* ReduceLROnPlateau
* ModelCheckpoint

---

## Results

| Metric              | Value      |
| ------------------- | ---------- |
| Training Accuracy   | ~97%       |
| Validation Accuracy | 93.81%     |
| Test Accuracy       | **93.00%** |

---

## Repository Structure

```text
Brain_Tumor_Classification_CNN.ipynb
README.md
requirements.txt
```

> **Note:** The trained `.keras` model is not included because it exceeds GitHub's file size limit. You can regenerate the trained model by running the notebook.

---

## Future Improvements

* Deploy as a web application
* Develop a mobile application
* Use EfficientNetB3/B4 for improved accuracy
* Integrate Explainable AI (Grad-CAM)
* Deploy using cloud services

---

## Author

**Shaktiraj Singh Chouhan**

Integrated M.Tech in Artificial Intelligence

VIT Bhopal University
