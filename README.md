# News Article Classification

## Assessment Report  
Submitted as partial fulfillment for the award of **Bachelor of Technology Degree (2024–25)**  
**CSE (AI)**  
By: **Dhruv Goel**  
Roll Number: 202401100300100  
Section: B  
Under the supervision of: **Shivansh Prasad**  
**KIET Group of Institutions, Ghaziabad**  
Date: April 22, 2025

---

## 📘 Introduction
This project classifies news articles into predefined categories: `tech`, `business`, and `sports`, using basic metadata like word count, presence of keywords, and read time. The problem involves **multi-class supervised machine learning**.

---

## ❓ Problem Statement
Automating the classification of news articles can enhance personalization, searchability, and reduce manual sorting efforts. The goal is to create a robust ML model that categorizes articles based on structured metadata.

---

## 🎯 Objectives
- Develop a classification model using metadata.
- Preprocess and encode data appropriately.
- Train a Random Forest classifier.
- Evaluate with metrics like **accuracy**, **precision**, **recall**.
- Visualize performance using a **confusion matrix**.

---

## 🔍 Methodology
- **Data**: `news_articles.csv` with 100 entries and 4 columns.
- **Preprocessing**: Label encoding for the target variable.
- **Modeling**: Split 80/20 train-test, Random Forest Classifier.
- **Evaluation**: Accuracy, Precision, Recall + heatmap of confusion matrix.

---

## 🧼 Data Preprocessing
- Checked for missing values.
- Encoded labels using `LabelEncoder`.
- Selected features: `word_count`, `has_keywords`, `read_time`.

---

## 🤖 Model Implementation
Used `RandomForestClassifier` from `scikit-learn` on selected features with default parameters. Evaluated the model and visualized predictions.

---

## 📈 Evaluation Metrics
- **Accuracy**: Overall correctness.
- **Precision**: Correctly predicted positives.
- **Recall**: True positives captured.
- **F1 Score**: Balance of precision and recall.
- **Confusion Matrix**: Visual insight into misclassifications.

---

## 📊 Results
- All metrics (accuracy, precision, recall, F1 score) ≈ **0.40**
- Confusion matrix shows category overlaps.
- Performance is limited by dataset size and basic features.

---

## ✅ Conclusion
The model demonstrates foundational ML concepts. While performance was moderate, expanding data and enhancing features can yield better results. The project gave practical experience in model building, evaluation, and visualization.

---

## 🧾 Dataset
- **File**: `news_articles.csv`
- **Features**:
  - `word_count`: Number of words in the article.
  - `has_keywords`: Boolean indicator for keyword presence.
  - `read_time`: Estimated time to read.
  - `category`: Target variable (tech, business, sports)

---

## 🛠️ Technologies Used
- Python 3 (Google Colab)
- pandas
- scikit-learn
- seaborn
- matplotlib

---

## ▶️ How to Run

1. Clone the repository or download the project files.
2. Make sure you have the required libraries installed:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
