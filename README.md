# Fake_internship_detection-System-Phase-1-EDA-Preprocessing
It is Phase 1 of a System that detects fake job/internship postings. In it the process of EDA and preprocessing has been completed.

## Project Overview

This project focuses on the exploratory data analysis (EDA) and preprocessing of a Fake Internship Posting Detection dataset. The goal is to clean, transform, and prepare the dataset for machine learning classification models that can identify fraudulent internship postings.

The project was completed as part of an AI/Machine Learning internship assignment.

---

## Problem Statement

Fake internship advertisements have become increasingly common on online recruitment platforms. These fraudulent postings may mislead students and job seekers through fake job offers, registration fees, phishing attempts, or identity theft.

The objective of this project is to preprocess internship posting data so that it can be used to train machine learning models for detecting fake internship postings.

---

## Dataset

- **Dataset Name:** Fake Internship Detection Dataset
- **Source:** Kaggle
- **Type:** Binary Classification
- **Target Variable:** `is_fake_posting`
  - **0** = Genuine Internship
  - **1** = Fake Internship

---

## Project Structure

```
Fake-Internship-Detection/
│
├── fake_internship_detection_dataset.csv
├── Fake_Internship_EDA_Preprocessing.ipynb
├── One_Page_Report.pdf
├── README.md
```

---

## Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset dimensions
- Feature names
- Data types
- Statistical summary
- Missing value analysis
- Duplicate record analysis
- Class distribution
- Data visualizations

Visualizations include:

- Class Distribution
- Stipend Distribution
- Missing Values
- Correlation Heatmap
- Boxplots for Numerical Features

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Date feature engineering
- TF-IDF Vectorization
- One-Hot Encoding
- Frequency Encoding
- Binary Encoding
- Ordinal Encoding
- Missing value imputation
- Duplicate removal
- Outlier detection and treatment (IQR)
- Feature scaling using StandardScaler
- Class imbalance analysis

---

## Technologies Used

- Python
- Jupyter Notebook

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Fake-Internship-Detection.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook in Jupyter Notebook.

4. Run all cells from top to bottom.

---

## Output

The notebook produces:

- Exploratory Data Analysis
- Data Quality Report
- Data Visualizations
- Cleaned and Preprocessed Dataset
- Machine Learning Ready Data

---

## Author

**Ayesha Qureshi**

BS Computer Science

Bahria University Lahore Campus

AI & Machine Learning Internship Project
