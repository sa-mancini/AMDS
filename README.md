# [P5] Building a Recommendation System with Collaborative Filtering using Alternating Least Squares (ALS) algorithm
Algorithms for Massive Datasets (2024/2025 edition)

## 📁 Files

- [`Report.pdf`](Report.pdf): Final report summarizing methodology, experiments, and results.
- [`ALS-Subsampled.ipynb`](ALS-Subsampled.ipynb): Full Jupyter notebook implemention on a substantially subsampled dataset using a standard Python version.
- [`ALS-Spark.ipynb`](ALS-Spark.ipynb): Full Jupyter notebook implemention on a large-scale distributed version using Apache Spark 3.5.1.

## 📚 Project Description

As part of the university coursework, I built a **Recommendation System** based on **Collaborative Filtering** using the Alternating Least Squares (**ALS**) matrix factorization algorithm, implemented from scratch. Two solutions were differentiated in order to evaluate scalability:  (i) a standard Python version on a substantially subsampled dataset, and (ii) a large-scale distributed version using Apache Spark. Both models were trained on a subset of user-book rating data, and evaluated against random and popularity-based baselines. Raw and latent spaces are compared using dimensionality reduction (PCA), cluster analysis, and performance metrics interpretation.
