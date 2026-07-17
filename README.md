# Gaussian Mixture Model using Expectation-Maximization (EM) Algorithm

## Project Objective

The objective of this project is to implement the Gaussian Mixture Model (GMM) using the Expectation-Maximization (EM) Algorithm from scratch in Base R. The project demonstrates how GMM performs probabilistic clustering by assigning each observation a probability of belonging to each cluster. The implementation is completed without using any external machine learning or clustering libraries.

---

## Software Used

- R
- Base R
- R GUI / RStudio
- Git
- GitHub

---

## Dataset

A synthetic dataset containing **20,000 observations** was generated using Base R.

Features:
- X1
- X2

The dataset contains two Gaussian clusters and is saved as:

**synthetic_data.csv**

---

## Steps to Run the Program

1. Open **gmm_em_algorithm.R** in R GUI or RStudio.
2. Run the complete program.
3. The synthetic dataset is generated and saved as **synthetic_data.csv**.
4. The EM Algorithm initializes the model parameters.
5. The Gaussian Density Function is calculated.
6. The Expectation (E-Step) computes the responsibility matrix.
7. The Maximization (M-Step) updates the model parameters.
8. The algorithm repeats until convergence or 20 iterations.
9. The following output plots are generated inside the **Output** folder:
   - dataset.png
   - final_clusters.png
   - log_likelihood.png

---

## Project Folder Structure

```
GMM-EM-Algorithm-Week1/
│
├── README.md
├── gmm_em_algorithm.R
├── synthetic_data.csv
├── Week1_Report.pdf
│
└── Output/
    ├── dataset.png
    ├── final_clusters.png
    └── log_likelihood.png
```

---

## Output Screenshots

### 1. Synthetic Dataset
- Scatter plot of the generated Gaussian clusters.
  <img width="672" height="669" alt="Synthetic Dataset" src="https://github.com/user-attachments/assets/c33bc040-31e1-415b-bf5b-ba8d0205d20b" />


### 2. Final Cluster Assignment
- Scatter plot showing the clusters identified by the EM Algorithm.
- <img width="671" height="667" alt="Final Clusters" src="https://github.com/user-attachments/assets/372288d9-2cc5-4453-9452-a5d91d00a736" />


### 3. Log-Likelihood Plot
- Graph showing the Log-Likelihood value for each iteration until convergence.
- <img width="673" height="667" alt="EM Convergence" src="https://github.com/user-attachments/assets/2776fc40-1dfd-4620-9d24-d82caa90a651" />


---

## Learning Outcomes

After completing this project, I learned to:

- Understand the concept of unsupervised learning.
- Differentiate between K-Means and Gaussian Mixture Models.
- Generate a synthetic dataset using Base R.
- Implement the Multivariate Gaussian Probability Density Function.
- Perform the Expectation (E-Step).
- Perform the Maximization (M-Step).
- Update mixing coefficients, mean vectors, and covariance matrices.
- Compute Log-Likelihood values.
- Check the convergence of the EM Algorithm.
- Visualize clustering results using Base R.
- Upload the completed project to GitHub.

---

## Author

**Student Name:** Prathibaa P

**Course:** BCA

**Project:** Week 1 – Gaussian Mixture Model using EM Algorithm

**Language:** R (Base R)
