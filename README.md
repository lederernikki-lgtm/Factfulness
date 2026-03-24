# Global Development Clustering Analysis

## Overview
This project explores whether the world can meaningfully be divided into only two groups of countries — **developed** and **developing**. Using **K-Means clustering** on global development indicators, the analysis investigates how many natural groupings actually exist in the data and compares the findings with the ideas presented in *Factfulness* by Hans Rosling.

## Research Questions
- Can the world be meaningfully divided into only two clusters (developed vs developing)?
- How many clusters are suggested by the data according to the **Elbow Rule**?
- How much of the data structure is explained by two clusters compared to the optimal number of clusters?
- Does the evidence support the claim in *Factfulness* that the world cannot be divided into only two groups but into four?

## Methodology
1. Collected global development indicators for multiple countries.
2. Cleaned and standardized the data.
3. Applied **K-Means clustering** to group countries based on similarities.
4. Used the **Elbow Rule** to determine the optimal number of clusters.
5. Compared the explanatory power of a **two-cluster model** with the optimal clustering solution.

## Results
- The world **cannot be meaningfully divided into only two clusters**.
- The **Elbow Rule suggests 5 clusters** as the optimal number.
- A **two-cluster model explains only 35.91%** of the structure in the data.
- The results **support the claim in *Factfulness*** that global development should not be viewed as a simple developed vs developing divide.

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib

## How to Run
```bash
git clone https://github.com/yourusername/global-development-clustering.git
cd global-development-clustering
pip install -r requirements.txt
jupyter notebook
