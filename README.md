# MLPR_Project
Lung Cancer Detection through Hyper-Resolution Stacking

# Lung Cancer Detection Using Super-Resolution Stacking

### Authors
**Abhilash Bindal, Dhruv Pande, Rishaan Damani**

---

## 📘 Overview

Lung cancer accounts for nearly **1.8 million deaths annually** and remains one of the deadliest forms of cancer due to late diagnosis. Early detection, especially of pulmonary nodules via CT scans, can significantly improve survival rates. However, traditional manual interpretations are **time-consuming**, **subjective**, and suffer from **inter-observer variability**.

Our project proposes a **novel machine learning framework** that integrates **multi-resolution super-resolution stacking** with a **3D Convolutional Neural Network (3D-CNN)** to enhance nodule detection and segmentation.

---

## 🧠 Core Problem

While most machine learning models work on **2D slices**, they often **ignore volumetric context and resolution variability**, resulting in:

- Inaccurate boundary detection
- Suboptimal volume estimation
- Missed small nodules or misidentified anatomical structures

---

## 🚀 Proposed Solution

We introduce a **super-resolution stacking method** using the **RIDER Lung CT dataset**, which includes scans at multiple slice thicknesses (1.25mm, 2.5mm, 5mm). This method fuses the multi-resolution data into a **high-detail volumetric input**, enabling:

- Improved **spatial detail** and **anatomical continuity**
- Enhanced **segmentation accuracy**
- Reduced **observer dependence**

This is paired with a **3D CNN model** that processes volumetric data and learns to identify lung nodules with better contextual understanding.

---

## 🧾 Key Features

- ✅ Super-resolution fusion of CT slices at different resolutions
- ✅ 3D Convolutional Neural Network architecture
- ✅ Volumetric segmentation of lung nodules
- ✅ Evaluation on RIDER Lung CT test-retest dataset

---

## 🔍 Background

### Why This Matters

- Lung cancer contributes to **25% of all cancer-related deaths**
- Nodules under 6mm are often missed in manual interpretations
- Variability in scan quality and slice thickness leads to inconsistent results

### Existing Limitations in CAD Systems

- Traditional 2D CAD lacks depth context
- Early systems used hand-crafted features, leading to high false positives
- Lack of generalizability across imaging protocols

---


## 🛠️ Methodology

1. **Data Acquisition**: RIDER Lung CT dataset with multiple slice thicknesses
2. **Super-Resolution Stacking**: Fusing images into one detailed volumetric input
3. **3D CNN Architecture**: Trained to detect and segment nodules
4. **Evaluation**: Compared against single-slice, single-resolution approaches

---

## 🧪 Results

Our model achieved:

- Enhanced boundary detection
- Improved sensitivity to small nodules
- Greater consistency across test-retest scans

These results show promise for integration into clinical workflows for **early-stage lung cancer detection**.

---

## 🏥 Clinical Relevance

- Aims to reduce inter-observer variability in diagnosis
- Supports radiologists in identifying subtle nodules
- Bridges the gap between AI performance and **real-world clinical utility**

---

## 📁 Dataset

**RIDER Lung CT Dataset**  
- Publicly available  
- Includes test-retest CT scans  
- Reconstructed at multiple slice thicknesses  

---

## 📌 Future Work

- Extend super-resolution stacking to other organs/tissues
- Incorporate transformer-based models for further context-aware learning
- Optimize for real-time clinical deployment and usability

---



---

## 📄 License

This project is for academic research purposes only. Please cite appropriately if used.

