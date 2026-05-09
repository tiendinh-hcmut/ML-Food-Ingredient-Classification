# 🍔 Food Ingredient Classification - Machine Learning Pipeline

## 📖 Course Information
- **Course Name:** Machine Learning
- **Course Code:** CO3117
- **Semester:** Semester II, Academic Year 2025-2026
- **Instructor:** Dr. Truong Vinh Lan

## 👥 Group 15 - Class CC01
| No. | Full Name | Student ID | Email | Role / Contribution |
|:---:|---|:---:|---|---|
| 1 | **Đinh Tiến (Leader)** | 2353174 | tien.dinh2110@hcmut.edu.vn | CNN Feature Extractor & Project Management |
| 2 | **Nguyễn Thành Tài** | 2353062 | tai.nguyen206k23@hcmut.edu.vn | Transformer Feature Extractor & Label Master |
| 3 | **Nguyễn Minh Trực** | 2353264 | truc.nguyenminh@hcmut.edu.vn | Machine Learning Classifiers |
| 4 | **Đinh An Huy** | 2352372 | huy.dinh30001@hcmut.edu.vn | Visual Analytics & Report Formatting |

## 🎯 Project Objectives
The primary goal of this project is to implement a complete traditional machine learning pipeline for image data, focusing on recognizing and classifying 315 food ingredient classes. The project aims to:
- Perform robust Exploratory Data Analysis (EDA) and data preprocessing.
- Extract deep features using CNN models (ResNet50, EfficientNetB0) and Transformer models (Vision Transformer - ViT).
- Train and evaluate classical machine learning classifiers (Logistic Regression, SVM, Random Forest) using the extracted features.
- Compare the feature representations and model performances using advanced visual analytics (PCA, t-SNE, Confusion Matrix).

## 📂 Directory Structure
The repository now uses a single integrated notebook approach.
```text
src/
├── notebooks/
│   └── main.ipynb                    # Main notebook with full EDA, preprocessing, feature extraction, and modeling
├── reports/
│   ├── feature_space_visualization.png
│   ├── hf_vit_training_history.png
│   ├── ml_results_all_features.csv
│   └── label_map.json
└── features/
    ├── resnet_X_train.npy
    ├── resnet_X_test.npy
    ├── effnet_X_train.npy
    ├── effnet_X_test.npy
    ├── vit_X_train.npy
    ├── vit_X_test.npy
    ├── vit_X_val.npy
    ├── y_train.npy
    ├── y_test.npy
    └── y_val.npy
```

> Note: All pipeline code is integrated inside `notebooks/main.ipynb`. The project is not split into separate Python modules for this version.

## ⚙️ How to Run the Code
Our pipeline is designed to be fully reproducible within a Google Colab environment. **No personal Google Drive mounting is required.**

1. **Open the Notebook:** Open `notebooks/Main_Pipeline.ipynb` in Google Colab.
2. **Environment Setup:** The notebook automatically installs all necessary dependencies (`datasets`, `transformers`, `torch`, `tensorflow`, `scikit-learn`, etc.) in the first cell.
3. **Data Acquisition:** The dataset is automatically downloaded directly from Hugging Face (`Scuccorese/food-ingredients-dataset`) into the Colab temporary storage.
4. **Execution:** On the top menu bar, click **Runtime -> Run all**.
5. **Output:** The notebook will sequentially execute EDA, preprocessing, feature extraction, and model evaluation without any manual intervention or external dependencies.

## 🔗 Project Links
* **Google Colab Notebook:** [Link](https://colab.research.google.com/github/tiendinh-hcmut/ML-Food-Ingredient-Classification/blob/main/notebooks/food_ingredient.ipynb)
* **Final PDF Report:** [Insert Link to PDF in Repo or Drive Here]
