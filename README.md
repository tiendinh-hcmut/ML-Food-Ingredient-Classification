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
The submission package and this repository strictly follow the required structure:
```text
Group15_FinalSubmission/
├── notebooks/
│   └── Main_Pipeline.ipynb        # The main Google Colab notebook
├── modules/
│   └── (Optional) helper_functions.py # Custom python modules if any
├── reports/
│   ├── ProgressReport_Phase1.pdf
│   ├── ProgressReport_Phase2.pdf
│   ├── ProgressReport_Phase3.pdf
│   └── FINAL_REPORT_Group15.pdf   # The comprehensive final report
└── features/
    ├── resnet_X_train.npy         # (Files are too large for GitHub, generated via Colab)
    ├── vit_X_train.npy            
    └── ...
```

## ⚙️ How to Run the Code
Our pipeline is designed to be fully reproducible within a Google Colab environment. **No personal Google Drive mounting is required.**

1. **Open the Notebook:** Open `notebooks/Main_Pipeline.ipynb` in Google Colab.
2. **Environment Setup:** The notebook automatically installs all necessary dependencies (`datasets`, `transformers`, `torch`, `tensorflow`, `scikit-learn`, etc.) in the first cell.
3. **Data Acquisition:** The dataset is automatically downloaded directly from Hugging Face (`Scuccorese/food-ingredients-dataset`) into the Colab temporary storage.
4. **Execution:** On the top menu bar, click **Runtime -> Run all**. 
5. **Output:** The notebook will sequentially execute EDA, preprocessing, feature extraction, and model evaluation without any manual intervention or external dependencies.

## 🔗 Project Links
* **Google Colab Notebook:** [Insert Google Colab Public Link Here]
* **Final PDF Report:** [Insert Link to PDF in Repo or Drive Here]
