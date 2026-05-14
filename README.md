# part-2-cnn-computer-vision
BITSOM Assignment 5\
  CNN Computer Vision

# Dataset Link
https://drive.google.com/drive/folders/17xoSIAe-24-18iJiN3zKPqJl-RNDqIeW


# CNN-Based Manufacturing Defect Detection

## Objective
Build a CNN model to classify manufacturing defects.

## Dataset
- normal
- scratch
- dent
- stain

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- Matplotlib
- Scikit-learn

## Workflow
1. Dataset Exploration
2. Preprocessing
3. CNN Model Building
4. Training
5. Evaluation
6. Predictions

## Results
- Training Accuracy
- Validation Accuracy
- Confusion Matrix
- Sample Predictions

## Task 6: CNN Concept Explanation 

Q1. What is Convolution?\
Convolution is the process where a small filter scans across the image to detect patterns such as:\
-edges\
-textures\
-shapes\
-defects\
The CNN automatically learns useful filters during training.

Q2. Why is Pooling Used?\
Pooling reduces image feature dimensions.\
**Benefits:**\
-Faster computation\
-Less memory usage\
-Reduced overfitting\
-Keeps important features\
Most common pooling: **Max Pooling** which keeps the strongest feature values.

Q3. Why is ReLU Commonly Used?\
**ReLU stands for:** Rectified Linear Unit\
**Function:** f(x)=max(0,x)\
**Benefits:**\
-Faster training\
-Solves vanishing gradient problems\
-Introduces non-linearity

Q4.Why are CNNs Better Than Feed-Forward Networks for Images?\
CNNs are better because they:\
-Preserve spatial relationships\
-Detect local visual patterns\
-Require fewer parameters\
-Automatically learn features\
Regular neural networks flatten images completely, losing spatial information.\
CNNs are specifically designed for image data.

## Task 7: Business Use Case Mapping

**Manufacturing Quality Inspection**\
This CNN-based defect classification system can be used in manufacturing industries for automated quality control.\
Example Workflow
1. Camera captures product image
2. CNN analyzes surface
3. System predicts:
-normal\
-scratch\
-dent\
-stain
4. Defective products are removed automatically\
**Benefits:**\
-Faster inspection\
-Reduced human error\
-24/7 monitoring\
-Lower operational cost\
-Improved product quality
