# Wine Dataset Clustering Algorithms 🍷

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)

An Unsupervised Machine Learning project exploring clustering techniques on the Wine dataset using multiple clustering algorithms. The project demonstrates the complete machine learning workflow including preprocessing, exploratory data analysis, dimensionality reduction, clustering, visualization, and evaluation.

---

## 📌 Project Overview

This project explores unsupervised learning on the classic Wine dataset using multiple clustering algorithms. The notebook walks through data loading, exploratory data analysis, preprocessing, dimensionality reduction, clustering, and model evaluation.

The Wine dataset contains:
- 178 wine samples
- 13 numerical chemical features
- Different wine cultivars

Although the dataset contains class labels, the labels are only used for external validation and are not included during clustering.

The project compares how different clustering algorithms perform on the same dataset after feature scaling and preprocessing.

---

## 🤖 Algorithms Used

The notebook includes the following clustering techniques:

- K-Means Clustering
- Agglomerative Clustering
- DBSCAN

---

## ⚙️ Workflow

The notebook follows this workflow:

1. Upload and extract the dataset
2. Load the dataset into a pandas DataFrame
3. Perform exploratory data analysis (EDA)
4. Review summary statistics and feature distributions
5. Standardize numeric features using `StandardScaler`
6. Reduce dimensions using PCA
7. Apply clustering algorithms
8. Evaluate clustering performance
9. Visualize clustering results

---

## 📊 Exploratory Data Analysis

The exploratory analysis highlights that the dataset features exist on different numerical scales. Since clustering algorithms are distance-based, feature scaling becomes an important preprocessing step.

The notebook uses:
- Summary statistics
- Correlation analysis
- Distribution plots
- PCA visualizations

to better understand the structure of the dataset before clustering.

---

## 📈 Evaluation Metrics

The clustering models are evaluated using metrics such as:

- Silhouette Score
- Adjusted Rand Index (ARI)

These metrics help measure:
- Cluster separation
- Cluster compactness
- Agreement with true wine classes

---

## 🏆 Results Summary

| Algorithm | Observation |
|-----------|-------------|
| K-Means | Produced well-separated clusters after scaling |
| Agglomerative Clustering | Captured hierarchical relationships effectively |
| DBSCAN | Detected dense regions but was sensitive to parameter tuning |

---

## 🛠️ Libraries Used

The project uses the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


## 📂 File Structure

```bash
Wine-Dataset-Clustering/
│
├── Wine_dataset_Clustering_Algorithms.ipynb
├── wine.zip
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/StephanieM3010/Wine-Dataset-Clustering.git
```

### 2. Navigate to the Project Directory

```bash
cd Wine-Dataset-Clustering
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open:

```bash
Wine_dataset_Clustering_Algorithms.ipynb
```

and run all cells from top to bottom.

---

## 📝 Notes

Some notebook cells are designed for Google Colab upload workflows. If running locally, you may need to adjust file path handling accordingly.

---

## 🔮 Possible Improvements

Future improvements could include:

- Elbow Method analysis for optimal K selection
- Additional clustering validation metrics
- Comparison before and after feature scaling
- Interactive visualizations
- Refactoring into reusable Python scripts
- Hyperparameter tuning for DBSCAN

---
# 👥 Team Contributions

This project was collaboratively developed by a team of 10 members, with each group handling different stages of the machine learning workflow.

| Project Section | Team Members | Responsibilities |
|----------------|--------------|------------------|
| **Step 1: Exploratory Data Analysis (EDA)** | Melanie Ouya & Stephanie Kirirgo | Data exploration, summary statistics, feature analysis, identifying patterns and scale differences |
| **Step 2: Data Preprocessing** | Melanie Ouya & Stephanie Kirirgo | Data cleaning, feature scaling, preprocessing using `StandardScaler` |
| **Step 3: K-Means Clustering** | Teddy Dan Mudanya & Mary Wamamba | Implementation of K-Means clustering and evaluation using internal and external metrics |
| **Step 3: Hierarchical Clustering** | Stacy Muhia & Margret Wangari | Implementation of Hierarchical Clustering and evaluation using internal and external metrics |
| **Step 3: DBSCAN Clustering** | Mercy Wanjiru & Brian Kibet | Implementation of DBSCAN clustering and evaluation using internal and external metrics |
| **Step 4: Evaluation Metrics** | Clustering Teams | Performance evaluation using metrics such as Silhouette Score and Adjusted Rand Index (ARI) |
| **Step 5: Visualization & PCA** | Joanna Furaha & Samara Mbala | PCA implementation, cluster visualization, plotting, and interpretation of clustering results |
| **Step 6: Final Compilation** | Entire Team | Combining findings, results interpretation, and project documentation |

---


## 📜 License

This project is open-source and available under the MIT License.

---
