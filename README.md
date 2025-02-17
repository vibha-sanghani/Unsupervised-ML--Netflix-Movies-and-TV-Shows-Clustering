# 🎬 Unsupervised-ML-Netflix-Movies-and-TV-Shows-Clustering

## 📌 Project Overview

This project applies **Unsupervised Machine Learning** techniques to analyze and cluster **Netflix Movies & TV Shows** based on various attributes such as genre, release year, rating etc. The goal is to identify patterns and similarities among the content, enabling better recommendations and insights into Netflix’s vast catalog.

## 🎯 Objectives

- 🔍 **Discover hidden patterns** in Netflix content.
- 🎭 **Cluster movies and TV shows** based on genre, release year, and other factors.
- 📊 **Analyze trends** in Netflix’s content distribution.
- 📈 **Provide insights** to enhance content recommendation systems.

## 📂 Dataset Details

The dataset contains key attributes such as:
- 📌 **Show ID** (Unique Identifier)
- 🎬 **Title** (Movie/TV Show Name)
- 📆 **Release Year**
- 🎭 **Genre**
- 🌍 **Country of Origin**
- ⏳ **Duration** (Movie length or number of seasons)
- ⭐ **Rating** (Content Rating) etc.

## 🔎 Approach & Methodology

1. **Data Preprocessing & Cleaning**
   - 🧹 Handling missing values, duplicates, and inconsistencies.
   - 🔢 Encoding categorical data for clustering.

2. **Exploratory Data Analysis (EDA)**
   - 📊 Identifying trends and correlations among movies & TV shows.
   - 📈 Visualizing distributions using **Matplotlib** and **Seaborn**.

3. **Feature Engineering**
   - 🎭 Transforming categorical features (e.g., genres) into numerical representations.
   - 🏗 Normalizing and scaling data for clustering.

4. **Clustering Algorithms**
   - 🚀 **K-Means Clustering**: Segmenting shows into meaningful clusters.
   - 🔍 ** Silhouette Score for Clustering**: metric used to evaluate.
   -   Used the silhouette method and k-means elbow method to find optimal number of clusters and built recommender system by cosine 
       similarity and recommended top ten movies

5. **Visualization & Insights**
   - 🎨 Cluster visualization using **PCA**.
   - 📊 Graphical representation of content clusters.
   
## 🛠 Tools & Technologies Used

- 🐍 **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- 📊 **PCA** for dimensionality reduction
- 🚀 **Unsupervised ML Algorithms** (K-Means,  Silhouette Score for Clustering)

## 🚀 Key Takeaways
- 📊 Built clusters that help in recommendation systems.
- 📈 Gained insights into Netflix’s content strategy.

## 📌 Conclusion
This project aimed to cluster TV shows and movies based on their similarities and differences, with the end goal of developing a content-based recommender system. The system suggests 10 shows to users based on their viewing history.

Here are some key takeaways from the project:

The dataset contained 7,787 records and 12 attributes, requiring careful handling of missing values and a thorough exploratory data analysis (EDA).

The analysis showed that Netflix has more movies than TV shows, with a growing collection of content from the United States.
To cluster the content, I focused on six key attributes: director, cast, country, genre, rating, and description (all categorical variables).

These attributes were transformed using TF-IDF vectorization, resulting in 9,000 features.

To tackle the curse of dimensionality, I applied Principal Component Analysis (PCA), reducing the feature space to 2,500 components while retaining over 80% of the variance.
I implemented the K-Means algorithm to cluster the shows. The elbow method suggested an optimal cluster count of 6, while the Silhouette score analysis indicated that 10 clusters provided better-defined groupings.

Building on these efforts, I developed a content-based recommender system using a cosine similarity matrix to measure show similarities.

The recommender system delivers personalized recommendations by analyzing the user's viewing history, leveraging content similarities to suggest ten highly relevant shows for an enhanced viewing experience






