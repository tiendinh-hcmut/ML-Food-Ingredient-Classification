# 🍔 Food Ingredient Classification - Machine Learning Pipeline

## 📖 Course Information
- **Course Name:** Machine Learning 
- **Course Code:** CO3117
- **Semester:** Semester II, Academic Year 2025-2026
- **Instructor:** Dr. Truong Vinh Lan

## 👥 Group 15 - Class CC01
| No. | Full Name | Student ID | Email | Role / Contribution |
|:---:|---|:---:|---|---|
| 1 | **Đinh Tiến (Leader)** | 2353174 | tien.dinh2110@hcmut.edu.vn | Feature Extraction, Conclusion, Future Work, Appendix & Source Code |
| 2 | **Nguyễn Thành Tài** | 2353062 | tai.nguyen206k23@hcmut.edu.vn | Introduction, Dataset Description, Exploratory Data Analysis (EDA), Model Training |
| 3 | **Nguyễn Minh Trực** | 2353264 | truc.nguyenminh@hcmut.edu.vn | Data Preprocessing, Deep Learning Pipeline, Comparison: Traditional ML vs Deep Learning |
| 4 | **Đinh An Huy** | 2352372 | huy.dinh30001@hcmut.edu.vn | Evaluation Metrics, Experimental Results, Advanced Analysis & Visualization, Discussion |

## 🎯 Project Objectives
The primary goal of this project is to implement a complete traditional machine learning pipeline and an end-to-end deep learning approach for image data, focusing on recognizing and classifying 315 food ingredient classes. The project aims to:
- Perform robust Exploratory Data Analysis (EDA) and data preprocessing.
- Extract deep features using CNN models (ResNet50, EfficientNetB0) and Transformer models (Vision Transformer - ViT).
- Train and evaluate classical machine learning classifiers (Logistic Regression, SVM, Random Forest).
- Implement an end-to-end Deep Learning pipeline (fine-tuning ViT) to compare with the traditional approaches.
- Compare the feature representations and model performances using advanced visual analytics (PCA, t-SNE, Confusion Matrix).

## 📂 Directory Structure
Based on the current repository and final submission requirements, the structure is organized as follows:
```text
ML-Food-Ingredient-Classification/
├── notebooks/
│   └── food_ingredient.ipynb              # The main Google Colab notebook
├── modules/
│   └── __init__.py                        # Custom python modules
├── reports/
│   ├── CO3117_CC01_Group15_Final_Report.pdf # The comprehensive final report
│   ├── feature_space_visualization.png    # PCA & t-SNE visualization outputs
│   ├── hf_vit_training_history.png        # Deep learning training history chart
│   ├── label_map.json                     # Mapping of integer indices to ingredient names
│   └── ml_results_all_features.csv        # Comprehensive metrics for all models
├── .gitignore
├── FinalReportTask.md                     # Task division markdown
└── README.md
```

## ⚙️ How to Run the Code
Our pipeline is designed to be fully reproducible within a Google Colab environment without requiring any personal Google Drive mounting.

1. **Open the Notebook:** Open the `notebooks/food_ingredient.ipynb` file in Google Colab via the provided link.
2. **Execution:** On the top menu bar, click **Runtime -> Run all**. The notebook will automatically handle dependency installation, dataset acquisition from Hugging Face, and execute the entire pipeline (EDA, preprocessing, feature extraction, and model evaluation).

## 🔗 Project Links
* **Google Colab Notebook:** [Link](https://colab.research.google.com/github/tiendinh-hcmut/ML-Food-Ingredient-Classification/blob/main/notebooks/food_ingredient.ipynb)
* **Final PDF Report:** [Link](https://drive.google.com/file/d/1UKr13rqXhwE1evGCACmyJopJj7Ul1Rqj/view?usp=sharing)
