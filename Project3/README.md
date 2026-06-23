
# Customer Segmentation using Unsupervised Learning

[cite_start]An enterprise data science pipeline that transforms raw, unlabeled consumer behavioral signals into mathematically isolated and strategically actionable market segments using Dimensionality Reduction and Clustering techniques[cite: 6, 8, 40].

## 📌 Project Overview
[cite_start]In modern enterprise analytics, shifting to unsupervised pattern discovery eliminates human cognitive bias, revealing subtle behavioral correlations across transactional variables[cite: 37]. [cite_start]This project implements a full Input-Process-Output (IPO) architecture to process customer features, handle high-dimensional spaces, and translate abstract cluster mathematical centers into clear business personas[cite: 8, 54, 55].

## 🏗️ Architecture Pipeline (IPO Model)
The chronological pipeline consists of four main architectural phases:
1. [cite_start]**SCALE:** Standardization of continuous features using $z$-score transformations to ensure equal mathematical voting power[cite: 56, 57, 85, 88].
2. [cite_start]**COMPRESS:** Principal Component Analysis (PCA) linear transformations to combat the Curse of Dimensionality and maximize variance retention[cite: 58, 59, 93, 103, 105].
3. [cite_start]**CLUSTER:** Iterative K-Means clustering optimization based on minimizing Within-Cluster Sum of Squares (WCSS)[cite: 60, 61, 132, 135].
4. [cite_start]**TRANSLATE:** Reverse-engineering synthetic PCA centroid coordinates back to human-centric physical dimensions[cite: 62, 63, 183, 185].

## 🛠️ Key Technical Requirements
* [cite_start]**Standardization:** Scales massive variations (e.g., Annual Income vs. Purchase Frequency) to prevent scale-induced proximity distortion[cite: 68, 77].
* [cite_start]**The 95% Rule:** Applies an Explained Variance Ratio threshold ($\sum EVR_i \ge 0.95$) to strip low-variance noise while keeping core signals intact[cite: 112, 114, 117].
* [cite_start]**Diagnostic Gatekeepers:** Employs the **Elbow Method** (inflection point of maximum curvature) and **Silhouette Scores** to mathematically prove the optimal number of clusters ($K$)[cite: 21, 144, 154].
* [cite_start]**Inverse Transforms:** Uses inverse mappings to map spatial abstract cluster coordinates back to physical features[cite: 185].

## 📈 Strategic Target Personas
[cite_start]The pipeline successfully isolates the following four distinct target consumer market segments[cite: 197]:
* [cite_start]**The Affluent Conservatives:** High income, low spending score[cite: 197].
* [cite_start]**The High-Value Trendsetters:** High income, high spending score[cite: 197].
* [cite_start]**The Budget-Conscious Explorers:** Lower income, high spending score[cite: 197].
* [cite_start]**The Conservative Minimizers:** Lower income, low spending score[cite: 197].

## 💻 Tech Stack & Packages
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (`StandardScaler`, `PCA`, `KMeans`)
* **Data Visualization:** `matplotlib`

## 🚀 How to Run the Notebook
1. Clone this repository.
2. Ensure you have your environment activated and dependencies installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
