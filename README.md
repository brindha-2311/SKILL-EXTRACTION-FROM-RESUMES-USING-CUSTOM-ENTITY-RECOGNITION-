# SKILL-EXTRACTION-FROM-RESUMES-USING-CUSTOM-ENTITY-RECOGNITION-

## 📄 Project Overview

This project presents a cloud-based **Custom Named Entity Recognition (NER)** system using **Amazon Comprehend** to extract **skills** from resumes automatically. Designed to streamline the recruitment process, this model identifies key technical and soft skills such as programming languages, tools, certifications, and more.

---
## 🔧 Tools & Technologies

- **Amazon Comprehend** – for training and deploying the custom entity recognizer
- **Amazon S3** – for dataset storage and retrieval
- **IAM Roles** – for secure access permissions
- **Python (with JSON & ZIP handling)** – for preprocessing resumes
- **Colab & KaggleHub** – for dataset access and manipulation
---

## 📁 Dataset Used

- **Resume Entities for NER** from Kaggle  
- Format: JSON → Converted into individual text files
- Entity Type Trained: `SKILLS`
---

## 📊 Evaluation Metrics

| Metric     | Value   |
|------------|---------|
| Precision  | 79.40%  |
| Recall     | 78.97%  |
| F1 Score   | 79.19%  |
---

## ✅ Results

The recognizer was able to detect various skills from unseen resumes such as:

- `Java`, `C++`, `SQL`, `AWS`, `Oracle`, `SAP`, `ERP`, `BI`, `Problem Solving`, etc.

All entities were identified with **high confidence scores (0.77 - 0.99)** and their positions in the text were tracked via character offsets.







