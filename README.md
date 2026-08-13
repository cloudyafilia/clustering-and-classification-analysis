# 📊 Clustering & Classification Analysis

A **Machine Learning project** developed as part of the Dicoding *Machine Learning for Beginners* course.

This project demonstrates an end-to-end machine learning workflow consisting of two main stages:

1. **Clustering** — discovering meaningful patterns and grouping observations based on their characteristics.
2. **Classification** — using the resulting data structure to build a supervised learning model for category prediction.

The project focuses on applying fundamental **unsupervised and supervised learning techniques** to a real-world dataset.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand the structure and characteristics of the dataset.
* Perform exploratory data analysis before modeling.
* Apply clustering to identify groups with similar characteristics.
* Analyze the resulting clusters.
* Use classification techniques to predict categorical outcomes.
* Evaluate the performance of the classification model.
* Apply an end-to-end machine learning workflow using Python.

---

# 🔄 Project Workflow

```text
              Dataset
                 │
                 ▼
        Data Understanding
                 │
                 ▼
       Exploratory Analysis
                 │
                 ▼
         Data Preprocessing
                 │
                 ▼
          ┌──────────────┐
          │  Clustering  │
          └───────┬──────┘
                  │
                  ▼
        Cluster Interpretation
                  │
                  ▼
          ┌──────────────┐
          │ Classification│
          └───────┬──────┘
                  │
                  ▼
          Model Evaluation
                  │
                  ▼
             Conclusion
```

---

# 🧩 Machine Learning Approaches

## 1. Clustering

The first stage applies **unsupervised learning** to discover groups within the observations without relying on predefined target labels.

The purpose of this stage is to:

* Identify naturally occurring groups.
* Discover similarities between observations.
* Understand patterns within the dataset.
* Generate additional information that can support the subsequent analysis.

The clustering analysis is implemented in:

```text
[Clustering]_Submission_Akhir_BMLP_Cloudya_Filia_Putri.ipynb
```

---

## 2. Classification

After the clustering stage, the project proceeds to **supervised learning**.

Classification is used to predict categorical outcomes based on the available features.

The classification analysis is implemented in:

```text
[Klasifikasi]_Submission_Akhir_BMLP_Cloudya_Filia_Putri.ipynb
```

The workflow includes:

```text
Feature Preparation
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Prediction
        ↓
Model Evaluation
```

---

# 📊 Data Analysis

Before applying machine learning algorithms, the project performs exploratory analysis to understand the dataset.

The analysis focuses on:

* Data types
* Missing values
* Feature distributions
* Relationships between variables
* Potential patterns in the observations

This step helps determine the appropriate preprocessing and modeling strategy.

---

# 🧹 Data Preprocessing

The preprocessing stage prepares the dataset for machine learning.

Typical preprocessing steps in the project workflow include:

* Checking data quality.
* Handling missing values where necessary.
* Selecting relevant variables.
* Transforming variables into suitable formats.
* Preparing features for clustering.
* Preparing features and target variables for classification.

The exact preprocessing implementation can be found in the corresponding notebooks.

---

# 🔬 Unsupervised Learning

Clustering is used to group observations based on similarity.

The general objective can be represented as:

```text
Input Data
    │
    ▼
Feature Representation
    │
    ▼
Clustering Algorithm
    │
    ▼
Cluster Assignment
    │
    ▼
Cluster Analysis
```

The resulting clusters can then be examined to understand the characteristics of each group.

---

# 🤖 Supervised Learning

The classification stage treats the relevant category as the target variable.

The model learns the relationship between:

```text
Input Features → Target Category
```

After training, the model generates predictions for previously unseen observations.

---

# 📏 Model Evaluation

Classification performance can be evaluated using several standard metrics, including:

### Accuracy

Measures the proportion of correctly classified observations.

### Precision

Measures how many observations predicted as a particular class are actually members of that class.

### Recall

Measures how many observations belonging to a particular class are successfully identified.

### F1-Score

Provides a balance between precision and recall.

### Confusion Matrix

Provides a detailed view of correct and incorrect predictions across classes.

The specific evaluation results are available in the classification notebook.

---

# 🛠️ Technologies

The project was developed using:

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

These tools support the complete workflow from data preparation and visualization to clustering and classification.

---

# 📁 Repository Structure

```text
clustering-and-classification-analysis/
│
├── [Clustering]_Submission_Akhir_BMLP_Cloudya_Filia_Putri.ipynb
├── [Klasifikasi]_Submission_Akhir_BMLP_Cloudya_Filia_Putri.ipynb
├── gun_clustered.csv
├── guns_incident.csv
└── README.md
```

The repository currently contains **7 commits** and is structured around separate notebooks for the clustering and classification stages.

### File Description

| File                    | Description                                       |
| ----------------------- | ------------------------------------------------- |
| Clustering Notebook     | Implementation of the unsupervised learning stage |
| Classification Notebook | Implementation of the supervised learning stage   |
| `gun_clustered.csv`     | Dataset containing the clustering results         |
| `guns_incident.csv`     | Original project dataset                          |
| `README.md`             | Project documentation                             |

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/cloudyafilia/clustering-and-classification-analysis.git
cd clustering-and-classification-analysis
```

## 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## 3. Run the Clustering Notebook

Open:

```text
[Clustering]_Submission_Akhir_BMLP_Cloudya_Filia_Putri.ipynb
```

Run the notebook sequentially to reproduce the unsupervised learning workflow.

## 4. Run the Classification Notebook

Open:

```text
[Klasifikasi]_Submission_Akhir_BMLP_Cloudya_Filia_Putri.ipynb
```

Run the notebook sequentially to reproduce the supervised learning workflow.

---

# 💡 Key Learning Outcomes

Through this project, the following machine learning concepts were explored:

* Exploratory Data Analysis
* Data preprocessing
* Unsupervised learning
* Clustering
* Cluster interpretation
* Supervised learning
* Classification
* Train-test splitting
* Model evaluation
* Data visualization
* End-to-end machine learning workflow

The project demonstrates how **clustering and classification can be incorporated into a single analytical workflow**, starting from discovering patterns in unlabeled data and continuing toward predictive modeling.

---

# 🔮 Future Improvements

Potential improvements for the machine-learning methodology include:

* Compare multiple clustering algorithms.
* Optimize the number of clusters using appropriate validation metrics.
* Compare multiple classification algorithms.
* Perform systematic hyperparameter tuning.
* Apply cross-validation.
* Add more comprehensive classification metrics.
* Use dimensionality reduction such as PCA for visualization.
* Add explainability techniques to better understand classification predictions.
* Develop an interactive dashboard for presenting analytical results.

---

# 👩🏻‍💻 Author

**Cloudya Filia Putri**

Statistics Student | Data Analytics & Machine Learning Enthusiast

---

## 🏷️ Topics

`Python` `Machine Learning` `Clustering` `Classification` `Unsupervised Learning` `Supervised Learning` `Data Analysis` `Scikit-learn` `Jupyter Notebook` `Data Science`
