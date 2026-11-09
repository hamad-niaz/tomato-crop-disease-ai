# Tomato Crop Disease Detection AI

An AI-based image classification project that detects 10 different tomato leaf conditions using Deep Learning and Transfer Learning.

## Project Overview

This project uses a pretrained ResNet18 model to classify tomato leaf images into 10 categories.

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab (GPU)

## Dataset

PlantVillage Tomato Dataset

- Total Images: 18,160
- Number of Classes: 10
- Training Images: 12,712
- Validation Images: 2,724
- Testing Images: 2,724

## Model Performance

| Metric | Result |
|---|---:|
| Model | ResNet18 |
| Test Accuracy | 91.67% |
| Test Loss | 0.2701 |
| Training Epochs | 5 |

## Project Features

- Tomato leaf disease classification
- Image preprocessing and augmentation
- Transfer learning using ResNet18
- Model evaluation and confusion matrix
- Prediction with confidence scores
- Model checkpoint saving

## Repository Structure

- `crop-disease-ai.ipynb`: Complete project implementation
- `requirements.txt`: Required Python libraries
- `.gitignore`: Files excluded from Git tracking

## Limitations

The model was evaluated using the PlantVillage dataset. Its performance on real-world field images has not yet been validated.
