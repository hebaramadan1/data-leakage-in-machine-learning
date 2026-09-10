# How to Detect and Prevent Data Leakage in Machine Learning
you can read the article:
 https://medium.com/@HebaRamadan./how-to-detect-and-prevent-data-leakage-in-machine-learning-a-practical-guide-to-building-reliable-ml-ba75c3a8c2dd

> A practical, research-oriented guide to understanding, detecting, and preventing Data Leakage in Machine Learning.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository accompanies the technical article **"How to Detect and Prevent Data Leakage in Machine Learning: A Practical Guide to Building Reliable ML Models"**, which explores how data leakage can lead to misleadingly high model performance and why proper evaluation methodology is essential for building reliable Machine Learning models.

---

## 📖 About the Article

Data Leakage is one of the most critical issues that can compromise the reliability of Machine Learning models. A model may achieve extremely high accuracy or excellent evaluation metrics while performing poorly on truly unseen data if information from the target or test set accidentally influences the training process.

This work focuses on understanding:
* What Data Leakage is
* Why it happens
* Common types of Data Leakage
* How leakage affects model evaluation
* How to detect potential leakage
* How to prevent leakage during preprocessing and model development
* The importance of proper Machine Learning evaluation methodology

---

## 🔬 Research Focus

The main focus of this work is **reliable Machine Learning evaluation**. Rather than focusing solely on achieving high performance metrics, this study emphasizes building models using a sound methodology where evaluation results accurately represent expected performance on unseen data.

Particular attention is given to:
* Data Splitting & Train-Test Contamination
* Target Leakage
* Preprocessing & Feature Engineering
* Model Training & Evaluation
* Proper use of Scikit-learn Pipelines

---

## 💻 Practical Examples

The repository contains the practical code examples used throughout the article, demonstrating how different Machine Learning practices can introduce or prevent Data Leakage.

The implementation primarily utilizes:
* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**

---

## 🧠 Key Topics

| Topic | Description |
| :--- | :--- |
| **1. Data Leakage** | Understanding what Data Leakage means and why it creates overly optimistic models. |
| **2. Target Leakage** | Situations where information directly or indirectly related to the target variable leaks during training. |
| **3. Train-Test Contamination** | How test set information can unintentionally influence the training process. |
| **4. Data Preprocessing** | Performing scaling, encoding, and imputation without allowing test set information to leak. |
| **5. Feature Engineering** | Designing feature creation to avoid using information unavailable at prediction time. |
| **6. Model Evaluation** | Establishing a strict separation between training and unseen data for reliable evaluation. |
| **7. Scikit-learn Pipelines** | Organizing preprocessing and modeling steps to systematically eliminate leakage risk. |

---

## 🛠️ Technologies Used

* ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) **Python**
* ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) **Pandas**
* ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) **NumPy**
* ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) **Scikit-learn**
* ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) **Jupyter Notebook**

---

## 📂 Repository Structure

```text
Data-Leakage-in-Machine-Learning/
│
├── README.md
├── requirements.txt
└── Code/
    └── data_leakage_examples.ipynb
