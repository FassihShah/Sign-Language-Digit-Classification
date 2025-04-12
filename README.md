# Multiclass Classification of Sign Language Digits Using Deep Neural Networks 

This notebook implements a multiclass image classification model using PyTorch. It focuses on recognizing sign language digits (0–9) from RGB images.

## Classification Task
- Recognize hand gestures representing digits **0 to 9**
- Multiclass classification using a neural network built with PyTorch

## 📁 Dataset
- **Sign Language Digits Dataset** from: [Sign Language Digits Dataset - GitHub](https://github.com/ardamavi/Sign-Language-Digits-Dataset)
- Each class (digit) is represented by images of hand gestures in RGB format
- Data is organized into folders per class, e.g., `0/`, `1/`, ..., `9/`

## Key Components
- ✅ A custom **PyTorch Dataset class** `SignDataset` to handle image loading and preprocessing
- ✅ Neural Network implementation using `torch.nn` modules
- ✅ Model training and evaluation on digit classification task

## Technologies Used
- Python
- PyTorch
- torchvision
- PIL (for image processing)
- matplotlib (for visualization)

## Files
- `Sign_Language_Classification.ipynb`: Main notebook including custom dataset class and training logic

---
