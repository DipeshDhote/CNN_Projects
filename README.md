# 🌿 Plant Disease Detection  

This project aims to detect plant diseases using deep learning. A **VGG16** model has been fine-tuned with **PyTorch** to classify plant leaf images, achieving an **accuracy of 90%**.  

## 🚀 Features  
- **Pretrained VGG16 Model**: Transfer learning applied for improved performance.  
- **Image Classification**: Identifies whether a plant leaf is healthy or diseased.  
- **High Accuracy**: Achieves **90% accuracy** on the test dataset.  
- **End-to-End Pipeline**: Includes data preprocessing, model training, evaluation, and inference.  

## 📂 Project Structure  
- `data/` - Dataset containing images of healthy and diseased leaves.  
- `notebooks/` - Jupyter notebooks for model training and evaluation.  
- `models/` - Saved PyTorch model for inference.  
- `inference.py` - Script for predicting diseases from new images.  

## ⚙️ Requirements  
- Python 3.12 
- PyTorch  
- Torchvision  
- NumPy, Matplotlib  

## 🏆 Model Performance  
- **Architecture**: VGG16 (Fine-tuned)  
- **Loss Function**: Cross-Entropy Loss  
- **Optimizer**: Adam  
- **Accuracy**: **90%**  

This project provides a deep learning-based solution for early plant disease detection, assisting farmers and researchers in effective disease management. 🌱🔍  
