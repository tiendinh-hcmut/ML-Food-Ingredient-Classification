# 📊 Machine Learning Project Report
## Food Ingredient Classification

# 1. Introduction (Tai)
- Problem statement: Food ingredient classification from images
- Objectives:
  - Apply traditional ML pipeline
  - Compare different feature extraction methods (CNN, Transformer)
- Dataset overview (short)

---

# 2. Dataset Description (Tai)
- Source: HuggingFace (food-ingredients-dataset)
- Structure:
  - Columns: image, category, subcategory, ingredient
- Total samples
- Number of classes (category, subcategory, ingredient)

---

# 3. Exploratory Data Analysis (EDA) (Tai)

## 3.1 Data Structure
- Number of rows, columns
- Data types

## 3.2 Missing Values
- Missing count + percentage
- Visualization (missingno matrix)
- Conclusion: how missing data is handled

## 3.3 Distribution Analysis
- Category distribution
- Subcategory distribution (top 15)
- Ingredient distribution (top 20)

## 3.4 Class Imbalance
- Bar chart / histogram
- Boxplot for ingredient counts
- Insight: imbalance level

## 3.5 Image Analysis
- Sample images visualization
- Image width & height distribution
- Insight: need for resizing (224x224)

---

# 4. Data Preprocessing (Truc)

## 4.1 Label Cleaning
- Lowercase conversion
- Replace spaces/slashes

## 4.2 Duplicate Removal
- Hash-based image comparison
- Number of duplicates removed

## 4.3 Missing Data Handling
- Drop rows with missing labels/images
- Justification

## 4.4 Class Filtering
- Remove classes with < 10 samples
- Reason: avoid training issues

## 4.5 Train/Validation/Test Split
- Ratio: 70/15/15
- Stratified sampling

## 4.6 Image Processing
- Convert to RGB
- Resize to 224x224
- Save to structured folders

## 4.7 Parallel Processing
- Multi-threading using ThreadPoolExecutor
- Speed improvement explanation

---

# 5. Feature Extraction (Tien)

## 5.1 CNN Features

### ResNet50
- Pretrained on ImageNet
- Output: feature vectors

### EfficientNetB0
- Lightweight + efficient architecture
- Feature extraction process

## 5.2 Transformer Features

### Vision Transformer (ViT)
- CLS token extraction
- PyTorch implementation
- GPU acceleration

## 5.3 Output Files
- `.npy` files:
  - resnet_X_train/test
  - effnet_X_train/test
  - vit_X_train/val/test
  - y_train/val/test

---

# 6. Model Training (Tai)

## 6.1 Models Used
- Logistic Regression
- SVM (RBF kernel)
- Random Forest

## 6.2 Feature Scaling
- StandardScaler for LR & SVM
- No scaling for Random Forest

## 6.3 Training Strategy
- Train on extracted features
- Compare across:
  - ResNet
  - EfficientNet
  - ViT

---

# 7. Evaluation Metrics (Huy)

- Accuracy
- Precision (macro)
- Recall (macro)
- F1-score (macro)

---

# 8. Experimental Results (Huy)

## 8.1 Performance Table
- Show full results (from CSV)

## 8.2 Best Model
- Identify best combination (Model + Feature)

---

# 9. Advanced Analysis & Visualization (Huy)

## 9.1 Feature Space Visualization
- PCA plots
- t-SNE plots
- Compare:
  - ResNet vs ViT
- Insight: clustering quality

## 9.2 Confusion Matrix
- Normalized confusion matrix
- Interpretation

## 9.3 Error Analysis
- Top confused class pairs
- Possible reasons:
  - Visual similarity
  - Dataset imbalance

## 9.4 Model Comparison
- Bar charts (Accuracy, Precision, Recall, F1)
- Discussion

---

# 10. Discussion (Huy)

- Why some models perform better
- CNN vs Transformer comparison
- Limitations:
  - Dataset imbalance
  - Similar classes
- Strengths of pipeline

---

# 11. Deep Learning Pipeline (Truc)

- End-to-end DL approach (if implemented)
- Architecture used
- Training process
- Results

---

# 12. Comparison: Traditional ML vs Deep Learning (Truc)

- Accuracy comparison
- Speed / complexity
- Pros & cons

---

# 13. Conclusion (Tien - Base on 10 and 12)

- Summary of findings
- Best model
- Key insights

---

# 14. Future Work (Tien)

- Data augmentation
- Fine-tuning models
- Larger dataset

---

# 📎 Appendix (Tien - reconstruct the source code folder structure first. Rewrite readme base on final report)
- Link to Colab Notebook
- GitHub repository