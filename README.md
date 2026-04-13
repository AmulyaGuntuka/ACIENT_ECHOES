# 🏛️ Ancient Echoes – AI-Driven Restoration of Manuscripts & Artifacts

## 📖 Overview
Ancient Echoes is an AI-powered project designed to restore damaged historical manuscripts, murals, and artifacts. Over time, these cultural assets degrade due to environmental conditions, aging, and physical damage.

This project provides a fully automated deep learning pipeline that detects damaged regions and restores them while preserving the original structure, texture, and color.

---

## ✨ Features
- Automatic damage detection (no manual masking required)  
- Deep learning-based restoration  
- Preserves original texture and color consistency  
- Multi-model ensemble for better accuracy  
- OCR-based text extraction from manuscripts  
- End-to-end automated pipeline  

---

## 🎯 Objectives
- Detect damaged areas in images automatically  
- Restore missing or degraded regions  
- Maintain historical and visual authenticity  
- Extract text from restored manuscripts  
- Provide scalable and efficient restoration  

---

## 🧠 Methodology

### 1. Damage Detection
- Uses HSV color space  
- Identifies cracks, faded regions, and erosion  
- Generates a damage mask automatically  

### 2. Image Restoration Models
- LaMa (Pretrained Inpainting Model)  
- RestorationNet (ResNet34-based CNN)  
- RefinementNet (Detail enhancement)  
- DunhuangRefiner (Residual correction models)  

### 3. Parallel Processing
- Two branches process the image simultaneously:
  - Pretrained model branch  
  - Custom deep learning branch  

### 4. Weighted Ensemble
- Combines outputs of all models  
- Improves accuracy and robustness  

### 5. Final Output
- Restored region is merged with original image  
- Ensures no changes to intact regions  

---

## 🏗️ System Architecture
<img width="288" height="403" alt="image" src="https://github.com/user-attachments/assets/ba68c7d6-eced-4f8f-87a4-489f2e8fadb7" />


---

## 📊 Results
The model is evaluated using:

- **PSNR (Peak Signal-to-Noise Ratio)**  
- **SSIM (Structural Similarity Index)**  
- **Masked Region Error**

### 🔹 Sample Outputs
<img width="843" height="421" alt="image" src="https://github.com/user-attachments/assets/2ff911bf-f9b8-445e-b634-58e12206a5eb" />
<img width="735" height="350" alt="image" src="https://github.com/user-attachments/assets/aa8c92e6-8180-4280-aad3-9a104dd02754" />
<img width="709" height="354" alt="image" src="https://github.com/user-attachments/assets/e2c7698d-8248-41cf-bfb7-93c46612d2c7" />

---

## 📂 Dataset
- Dunhuang Mural Dataset (Kaggle)  
- DIV2K Dataset  

---




