# Mpox-Skin-Lesion-Detection-and-Real-Time-Monitoring-in-a-Smart-Healthcare-System
Official implementation of ITMA'INN: A Smart Healthcare System for Mpox Skin Lesion Detection and Real-Time Monitoring. Includes deep learning models (ViT, MobileViT, ResNetViT, TNT, etc.), preprocessing pipelines, training scripts, and dashboard integration. This study is under revision in Q1 Journal.
- **Submitted:** 04 August 2025  
- **Revised:** 27 September 2025  
- **Accepted:** Pending

  ## 📂 Research Paper Refrence:
  - https://www.mdpi.com/2075-4418/15/19/2505
    

##### This repository contains the official implementation of **ITMA'INN**, an AI-powered healthcare system for early detection and monitoring of Monkeypox (Mpox) skin lesions.  

The system integrates:  
- **Deep Learning Models**: Transformer-based (ViT, MobileViT, ResNetViT, TNT, Swin) and CNN-based baselines (VGG16, ResNet50, EfficientNet-B0).  
- **Preprocessing Pipeline**: Image augmentation, normalization, resizing.  
- **Training & Evaluation Scripts**: For binary and multiclass classification (6-class and 4-class).  
- **Dashboard Integration**: Real-time monitoring for health authorities using Power BI.  
- **Mobile Application**: Cross-platform (Android/iOS) app for user-side lesion detection and reporting.  

---

## 📂 Repository Structure  



---

## 📊 Datasets  

We used three publicly available datasets (Kaggle):  
1. **MSLD** – Binary classification (Mpox vs Non-Mpox).  
2. **MSLD v2.0** – Multiclass (6 classes: Mpox, Chickenpox, Measles, Cowpox, HFMD, Healthy).  
3. **MSID** – Multiclass (4 classes: Mpox, Chickenpox, Measles, Normal), also used for external validation.  

🔗 Dataset links are provided in the manuscript and can be accessed through Kaggle.  

---

## ⚙️ Environment Setup  

- Python: `3.10.12`  
- PyTorch: `2.3.1`  
- Torchvision: `0.18.1`  
- TIMM: `1.0.8`  
- scikit-learn: `1.5.1`  
- Torchinfo: `1.8.0`  
- Matplotlib: `3.9.2`  
- TQDM: `4.66.5`  
- Pillow: `10.3.0`  

To install dependencies:  
```bash
pip install -r requirements.txt
```
---

## 📂 Citation 
``` 
Alghoraibi, Huda, Nuha Alqurashi, Sarah Alotaibi, Renad Alkhudaydi, Bdoor Aldajani, Joud Batawil, Lubna Alqurashi, Azza Althagafi, and Maha A. Thafar. "Deep Learning-Based Mpox Skin Lesion Detection and Real-Time Monitoring in a Smart Healthcare System." Diagnostics 15, no. 19 (2025): 2505.

```



