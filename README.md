#  Iris Dataset Clustering with K-Means

This project implements unsupervised learning on the Iris dataset using the K-Means clustering algorithm. The goal is to group similar flowers based on sepal and petal dimensions without using labeled data. The clusters are evaluated against the true species for comparison and visualized using 2D plots.

---

##  Table of Contents

- [Abstract](#abstract)
- [Technologies Used](#technologies-used)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Visualization](#visualization)
- [Results](#results)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Author](#author)

---

##  Abstract

Clustering is a powerful technique for discovering patterns in unlabeled data. This project applies the K-Means algorithm to the Iris dataset — one of the most famous classification datasets in machine learning. The model divides the dataset into three clusters representing the natural groupings of the iris species. Results are visualized with matplotlib to compare actual species labels with predicted clusters.

---

##  Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn (KMeans)  
- Jupyter Notebook

---

##  Dataset Description

- **Source**: UCI Machine Learning Repository / scikit-learn  
- **Records**: 150 samples  
- **Features**:
  - Sepal Length (cm)  
  - Sepal Width (cm)  
  - Petal Length (cm)  
  - Petal Width (cm)  
- **Target (for evaluation)**:
  - Iris-setosa  
  - Iris-versicolor  
  - Iris-virginica

---

##  Methodology

1. **Data Preprocessing**  
   - Load dataset  
   - Remove labels (unsupervised setting)  
   - Standardization (optional)

2. **Model Building**  
   - Use `KMeans(n_clusters=3)`  
   - Fit on feature data  
   - Predict cluster assignments

3. **Evaluation**  
   - Compare clusters to actual labels  
   - Use color-coded scatter plots for visual inspection

---

## 📈 Visualization

- Scatter plots generated using `matplotlib.pyplot`
- Compared real species labels vs. K-Means cluster assignments
- Shows K-Means' ability to group Iris-setosa well and mixed overlap between versicolor and virginica

---

##  Results

- K-Means accurately identifies Iris-setosa as a distinct cluster  
- Some overlap between versicolor and virginica  
- Visualization highlights boundaries and misclustered samples  
- Project illustrates the limitations and strengths of unsupervised clustering

---

##  Usage

1. **Clone the Repository**
```bash
git clone https://github.com/Shishiramedagam/iris-kmeans-clustering.git
cd iris-kmeans-clustering
