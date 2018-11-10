---
layout: default
title: "Portfolio"
permalink: /portfolio/
tagline: "Brian McGuckin: Data Science Portfolio"
order: 1
---
<h1 style="text-align:center">Projects</h1>
<h2 id="eth_timeseries">
  <a href="https://github.com/brianmcguckin/thinkful_final_capstone">
    Ethereum Price Forecasting with Machine Learning
  </a>
</h2>
**An Application of Time Series Regression Models and Neural Networks**
- Ethereum price time series analysis, modeling and forecasting using ARIMA models & LSTM RNNs, evaluated on RMSE and executed in Python. Performed changepoint analysis, set window size to median regime length, and differenced for stationarity. Forecasting method is one-step-ahead out of sample using a rolling window, and was done using ETH series only and then with Granger-causal exogenous drivers.

![exog_results](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/exog_results.png 'exog_results')

[Notebook](https://nbviewer.jupyter.org/github/brianmcguckin/thinkful_final_capstone/blob/master/ethereum_price_forecasting_with_machine_learning.ipynb),
[Slides](https://github.com/brianmcguckin/thinkful_final_capstone/blob/master/ethereum_price_forecasting_with_machine_learning.pdf)

**Topics:** Time Series, Forecasting, Cryptocurrency, ARIMA, LSTM, RNN, Structural Breaks, Stationarity, Exogenous drivers, Granger Causality

**Toolkit:** Python, Jupyter, Numpy, Pandas, Matplotlib, Seaborn, SciPy, Ruptures, FBProphet, Sci-kit Learn, Statsmodels, Tensorflow, Keras, Hyperopt, Hyperas

<h2 id="predicing_house_prices">
  <a href="https://github.com/brianmcguckin/thinkful_unit_03_capstone">
    Predicting Residential House Prices
  </a>
</h2>
**Regularized Linear Regression & Tree Based Ensemble Modeling with Ordinal Variables**
- Residential house price prediction using the [Ames, Iowa Housing Market Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) with a focus on ordinal variable treatment. EDA, address outliers, missing values, feature engineering/variable transformation. Ordinal data was treated as (1) all categorical, (2) all continuous, (3) mix of categorical/continuous. Modeled using regularized linear regression (l1/l2/elastic net), random forests, and gradient boosted decision trees (xgboost algorithm). Results evaluated on RMSE (primary metric) and model runtime (secondary).

![results table](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/house_price_results.png 'results table')

[Notebook](https://nbviewer.jupyter.org/github/brianmcguckin/thinkful_unit_03_capstone/blob/master/unit_03_capstone_final_notebook.ipynb), [Slides](https://github.com/brianmcguckin/thinkful_unit_03_capstone/blob/master/slides_housing_price_capstone.pdf)

**Topics:** data preprocessing, visualization, feature engineering, machine learning, regression

**Toolkit:** Python, Jupyter, NumPy, Pandas, Matplotlib, Seaborn, SciPy, SKLearn, XGBoost

<h2 id="reuters_text_classification">
  <a href="https://github.com/brianmcguckin/thinkful_unit_04_capstone">
    Reuters-21578 Text Classification
  </a>
</h2>
**NLP using Unsupervised Learning Methods for Article Classification**
NLP focused project tasked with utilizing unsupervised learning methods to classify topics for articles in the [Reuters-21578 Dataset](https://archive.ics.uci.edu/ml/datasets/reuters-21578+text+categorization+collection). Articles loaded, cleaned, classes inspected. Created featuresets and vectorized text using tf-idf. Clustering algorithms (k-means, spectral, mean-shift, affinity propagation) categorized article topics with two forms of dimension reduction (LSA & UMAP). Evaluated using ground truth clusters and ARI. Then used supervised classification algorithms (logistic regression, xgboost, KNN, random forest) and evaluated on cross-validated accuracy score.

![nn_clusters](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/nn_clusters.png 'spectral clustering nearest neighbors')

![xgb results](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/nlp_xgb.png 'xgboost results')
![lr results](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/nlp_logregr.png 'logregr results')

[Notebook](https://nbviewer.jupyter.org/github/brianmcguckin/thinkful_unit_04_capstone/blob/master/04_capstone_unsupervised_learning_final.ipynb)

**Topics:** text cleaning, tokenization, vectorization, dimensionality reduction, machine learning, clustering, classification

**Toolkit:** Python, NumPy, Pandas, Matplotlib, Seaborn, NLTK, SciPy, SKLearn, XGBoost, RegEx, UMAP
