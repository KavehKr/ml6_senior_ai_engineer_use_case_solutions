# AI Engineer Case Study – ML Solutions

This repository contains my solutions for two machine learning use cases, developed as part of an AI/ML engineering case study.

The focus is on building **practical, scalable solutions** that combine strong machine learning foundations with real-world applicability.

---

## 👤 Author
**Kaveh Kasaee Roodsari**  
Senior AI/ML Engineer

---

## 📌 Overview

This project addresses two different challenges:

### 📊 Use Case 1 – Clustering Sensor Data
- **Objective:** Extract meaningful insights from machine breakdown data with very limited labeled examples  
- **Challenge:** Only 40 labeled samples out of 1,600 data points  
- **Approach:**  
  - Semi-supervised learning  
  - Feature selection (ANOVA)  
  - Random Forest for pseudo-labeling  
  - Similarity-based validation  
  - Clustering (KMeans) to analyze remaining data  
- **Implementation:** `sensor_data_notebook.ipynb`

---

### ⚽ Use Case 2 – Sports Video Analytics
- **Objective:** Count players per team in a soccer match video  
- **Approach:**  
  - Computer vision pipeline  
  - Person detection  
  - Feature extraction  
  - Clustering-based team assignment  
- **Details:** Explained in the presentation

---

## ⚙️ Setup

Install dependencies:

```bash
pip install -r requirements.txt