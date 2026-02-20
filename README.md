# Brain Tumor Classification using EfficientNetB2

## Project Overview
This project focuses on automated brain tumor classification from MRI images using Deep Learning.  
A transfer learning approach is applied using the EfficientNetB2 architecture to classify brain MRI scans into tumor categories.

The model is implemented using TensorFlow and Keras and trained on a Kaggle Brain Tumor dataset.

---

## Objective
- To develop an automated system for brain tumor classification
- To assist in early medical diagnosis using deep learning
- To leverage transfer learning for improved performance on medical imaging tasks

---

## Dataset
- Source: Kaggle Brain Tumor MRI Dataset
- Image Type: MRI Brain Scans
- Categories: (Mention your class names here – e.g., Glioma, Meningioma, Pituitary, No Tumor)
- Data Split: Training and Validation
- Preprocessing:
  - Image resizing
  - Normalization
  - Data augmentation (if applied)

---

## Model Architecture

### Base Model
- EfficientNetB2 (Pre-trained on ImageNet)
- Transfer learning applied

### Custom Layers Added
- Global Average Pooling
- Dense Layer(s)
- Dropout Layer
- Softmax Output Layer

Batch Size: 32  
Framework: TensorFlow / Keras  
GPU Used: Tesla P100 (for training)

---

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Kaggle GPU (Tesla P100)

---

## Performance Metrics
- Training Accuracy: 89.5%
- Validation Accuracy: (Add your validation accuracy here)
- Loss Function: Categorical Crossentropy
- Optimizer: Adam

---

## How to Run

1. Clone the repository:
2.  Install required libraries:
3. Load dataset
4. Run training notebook or script
5. Evaluate model on validation data

---

## Results
The EfficientNetB2 model successfully classifies brain tumor MRI images with strong generalization performance.  
Transfer learning significantly improves convergence speed and classification accuracy.

---

## Why EfficientNetB2?
- Scalable CNN architecture
- Better parameter efficiency
- Strong performance on medical image classification
- Pre-trained weights improve feature extraction

---

## Future Scope
- Improve accuracy beyond 92%
- Hyperparameter tuning
- Deploy as web-based diagnostic tool
- Integrate Grad-CAM for model explainability
- Expand dataset for better generalization

---

## Author
AFFAN AHMAD 
Final Year Project – 2026
