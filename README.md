# 👕 Multi-Object Apparel Detection & Segmentation

**Akul Anhith (IMT2023558)**  
**Ramapuram Sreenivasa Raju (IMT2023122)**  
**Shashidhar Sai (IMT2023567)**  
**Sasank Reddy (IMT2023120)**  

VR Mini Project – IIIT Bangalore

---

## 🚀 Overview
End-to-end visual recognition system for fashion images:
- Multi-label classification  
- Object detection  
- Instance segmentation  

Dataset: DeepFashion2 (top 5 categories)

---

## 🧠 Models
**Classification:** ResNet-50, EfficientNet-B0, MobileNetV3  
**Detection & Segmentation:** YOLOv8, Mask R-CNN  
**Segmentation:** U-Net (semantic → instance)

---

## 📊 Dataset
- ~140K images  
- Train: ~120K | Val/Test: ~20K  
- Class imbalance handled using weighted loss  
- Models trained on sampled subsets (compute constraints)

---

## ⚙️ Training
- Scratch + Transfer Learning  
- Transfer:
  - Freeze backbone → train head  
  - Fine-tune full model (used selectively)  

---

## 📈 Evaluation
**Classification:** Precision, Recall, F1 (Macro/Micro), ROC-AUC  
**Detection:** mAP@0.5, mAP@[0.5:0.95], Precision/Recall  
**Segmentation:** mIoU, Dice  

---

