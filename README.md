# 🖼️ Image Segmentation & Captioning  

[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-Interactive%20UI-red)](https://streamlit.io/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange)](https://www.tensorflow.org/)  
[![PyTorch](https://img.shields.io/badge/PyTorch-Models-lightgrey)](https://pytorch.org/)  

A deep learning project developed during my internship that combines **image captioning** and **image segmentation** to provide descriptive captions and object-level understanding of images.  

---

## ✨ Features  
- 📝 **Image Captioning:** Generate meaningful captions for input images using a Transformer-based model.  
- 🎭 **Image Segmentation:** Detect and segment objects using **U-Net** or **Mask R-CNN**.  
- ⚡ **Interactive Web App:** Upload or provide image URLs and instantly view captions & segmentation masks via **Streamlit**.  
- 📦 **Pretrained Models:** Start quickly with provided weights or train your own models from scratch.  

---

## ⚙️ Installation  

Clone the repository and install dependencies:  

```bash
git clone https://github.com/your-username/Image_Segmentation_and_Captioning.git
cd Image_Segmentation_and_Captioning
```
This project requires Python 3.8+ and the following libraries:
```
pip install streamlit tensorflow torch torchvision numpy pandas pillow matplotlib opencv-python requests tqdm
```
```
├── app.py                     # Streamlit app for custom-trained models
├── Pretrain_app.py            # Streamlit app for pretrained ResNet50 version
├── Image_Caption_train.ipynb  # Notebook for training captioning model
├── image-segmentation.ipynb   # Notebook for training segmentation model
```
