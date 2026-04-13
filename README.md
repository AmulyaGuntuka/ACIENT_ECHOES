# 🏺 ANCIENT ECHOES  
### AI-Driven Restoration of Manuscripts & Artifacts  

## 📌 Overview  
Ancient Echoes is an AI-based system designed to restore degraded historical images such as murals and manuscripts.  
The project focuses on **automatic damage detection, inpainting, and refinement** using deep learning techniques.

This system provides a **fully automated restoration pipeline** without manual intervention.

---

## 🎯 Objectives  
- Detect damaged regions in historical images  
- Restore missing textures and colors  
- Preserve original artistic style  
- Improve visual quality using deep learning  
- Enable digital preservation of cultural heritage  

---

## 🧠 Methodology  

The system follows a **multi-stage pipeline**:

1. **Damage Detection**
   - Uses HSV + OpenCV techniques
   - Identifies cracks, fading, and erosion  

2. **Inpainting (LaMa Model)**
   - Handles large missing regions  
   - Generates structural restoration  

3. **Refinement (DunhuangRefiner)**
   - Applies residual correction  
   - Enhances textures and details  

4. **Weighted Ensemble**
   - Combines multiple model outputs  
   - Improves final quality  

---

## 🏗️ System Architecture  
<img width="280" height="217" alt="image" src="https://github.com/user-attachments/assets/08738ce5-53d4-4eab-b06b-c3214280c531" />


---

