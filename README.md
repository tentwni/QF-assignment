# QF-Assignment

Assignment submissions for the **tw_stock** group in Quantitative Finance.

## Group Members

- 李嘉鴻
- 林冠樺

## Repository Structure

```
assignment-1/
  └── QF_Homework.ipynb
```

## Assignment 1 — The Lognormal Function

This assignment covers the following topics:

- **Probability Theory**: Derivation of the mode, median, and mean of the lognormal distribution, with visualization of its PDF.
- **Elicitability**: Formal proof that the quantile is an elicitable functional using pinball (quantile) loss.
- **The Markov Property**: Proof of conditional independence using the chain rule of probability.
- **Copula Theory & Simulation**: Probability integral transform, bivariate Gaussian copula and Student-t copula simulations across varying correlation parameters.
- **Mean-Covariance Analysis**: Portfolio analysis using mean-covariance framework.

### Tools & Libraries

Python 3 with Finmind, NumPy, SciPy, and Matplotlib.

## How to Run

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Run all cells sequentially.

# Assignment 2 — Statistical Decision Theory & Estimation

This assignment covers the following topics:

- **Statistical Decision Theory**: Decision framework on `0050.TW` with state of nature, action space, and loss function.
- **Decision Scenarios**: Frequentist (momentum), Bayesian (posterior update), and Interventional (stop-loss) strategies vs. buy-and-hold.
- **Estimation Theory**: Estimation of $(\mu, \sigma)$ for `2330.TW` log returns via MLE, Normal-Inverse-Gamma Bayes, and Huber M-estimation.
- **Risk Decompositions**: Proofs of the MSE (bias–variance) and excess risk (approximation–estimation) decompositions.
- **Black-Litterman Model**: Classical Bayesian vs. Minimum Relative Entropy (Entropy Pooling) approaches.

## Tools & Libraries

Python 3 with yfinance, NumPy, SciPy, and Matplotlib.

## How to Run

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Run all cells sequentially.
