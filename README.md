# Iris_Clustering_KMeans_Hierarchical

To create a professional README for your GitHub repository, you can use the structure below. This is based on the contents of your Jupyter notebook, covering the objectives, methodology, and results of the Iris clustering project.

Iris Species Clustering: KMeans & Hierarchical Techniques
This project explores unsupervised machine learning by applying clustering algorithms to the classic Iris dataset. The goal is to discover underlying patterns and group flower samples based on their physical measurements without using predefined labels.

📋 Project Overview
In this assessment, the species labels are removed to treat the dataset as an unsupervised task. We compare two primary clustering methods to evaluate their effectiveness in identifying the three natural species of Iris (Setosa, Versicolor, and Virginica) based on sepal and petal dimensions.

🎯 Objectives
1. Apply KMeans and Hierarchical (Agglomerative) Clustering to a real-world dataset.
2. Preprocess data by handling duplicates and scaling features.
3. Visualize clusters and interpret results through feature-wise summaries.
4. Identify which algorithm performs best for this specific data structure.

📊 Dataset Description
The Iris dataset consists of 150 samples (reduced to 149 after removing duplicates) with four numerical features:

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

🛠️ Tech Stack
Language: Python

Libraries: * pandas, numpy (Data Handling)
    * matplotlib, seaborn (Visualization)
    * scikit-learn (KMeans, Agglomerative Clustering, Preprocessing)
    * scipy (Dendrograms)

📈 Methodology & Key Findings
1. Data Cleaning: The dataset was checked for missing values (none found) and duplicate entries were removed to ensure data integrity.
2. Feature Importance: Analysis showed that petal length and petal width are the most significant features for separating clusters, while sepal features showed more overlap.
3. KMeans: Chosen as the best algorithm for this project because the dataset is small and numerical, with a known number of compact, well-separated clusters (k=3).
4. Hierarchical Clustering: While effective, it was noted as the "worst" option here simply due to higher computational complexity without providing a significant improvement over KMeans.

🚀 Conclusion
Both algorithms successfully discovered the natural groupings within the data. The results demonstrate that clustering is a powerful tool for discovering similarities in data without the need for manual labeling.
