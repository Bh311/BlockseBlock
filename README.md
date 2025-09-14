# 🌸 Iris Dataset Visualization Project

## 📌 Project Overview
This project analyzes the **Iris Flower Dataset**, which contains measurements of sepal length, sepal width, petal length, and petal width for three iris flower species: **Setosa, Versicolor, and Virginica**.  
The goal is to create **data visualizations** using Seaborn and Matplotlib to identify patterns and insights.

---

## 📂 Dataset
- **Source**: Kaggle Iris Dataset
- **Columns**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species`

---

## 📊 Visualizations
1. **Distribution of Sepal Length** – Histogram with KDE curve.  
2. **Average Sepal Length by Species** – Bar plot comparing Setosa, Versicolor, Virginica.  
3. **Petal Length Distribution by Species** – Boxplot shows variation in petal length.  
4. **Sepal Width by Species** – Violin plot comparing distributions.  
5. **Pairplot** – Pairwise scatter plots colored by species (clear clustering).  

### 1. Distribution of Sepal Length
![Sepal Length Distribution](images/Histogram.png)

### 2. Average Sepal Length by Species
![Average Sepal Length](images/Barplot.png)

### 3. Petal Length Distribution by Species
![Petal Length Distribution](images/Boxplot.png)

### 4. Sepal Width by Species
![Sepal Width Distribution](images/Violinplot.png)

### 5. Pairplot of All Features
![Pairplot](images/Pairplot.png)

## 🔍 Insights
- **Setosa** flowers have distinctly smaller petals compared to other species.  
- **Versicolor** and **Virginica** overlap in sepal size but are separable by petal measurements.  
- **Petal length** is the most discriminative feature for classification.  
- The pairplot shows clear separation: Setosa is easily separable, while Versicolor and Virginica slightly overlap.  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

