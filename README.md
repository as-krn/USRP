# Multi-Disease Detection from Fundus Images using Deep Learning

## Project Overview
Fundus images are a vital medical imaging tool for evaluating eye health, enabling the diagnosis of diseases such as glaucoma, diabetic retinopathy, and hypertension. This project aims to develop an innovative system capable of multi-disease diagnosis from fundus images.

## Methodology
1. **Preprocessing:**  
   Fundus images are enhanced using **Contrast Limited Adaptive Histogram Equalization (CLAHE)** and **Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN)** to improve clarity and highlight key features.

2. **Hybrid Deep Learning Models with Attention Mechanisms:**  
   Hybrid versions of **MobileNetV2, EfficientNetB0, VGG16, and ResNet50** architectures are integrated with attention mechanisms to improve detection of small structures in the images. This approach enhances the performance of the models while overcoming the limitations of transfer learning.

3. **Cross-Validation and Data Diversity:**  
   Cross-validation is applied across datasets to ensure data diversity, allowing the model to encounter a wide range of images during training and improving generalization.

## Impact
The proposed system aims to provide accurate and fast analysis for the early diagnosis of multiple eye diseases, contributing significantly to the literature and clinical applications.

## Tools & Technologies
- Python  
- TensorFlow / Keras  
- OpenCV  
- CUDA  
- Google Colab  


