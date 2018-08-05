---
layout: default
---
# Data Science Portfolio
## Predicting House Prices
The goal of this project was to predict house prices using the [Ames, Iowa Housing Market Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). An Exploratory Data Analysis revealed outliers to exclude, missingness to address, variables to transform, and features to engineer. EDA also revealed many ordinal variables, which were treated categorically, continuously, and as a mix. Each treatment of ordinal data was modeled using parameter tuned algorithms including regularized linear regression, random forests, and gradient boosted decision trees. Results were primarily evaluated on root-mean-square error (RMSE), with secondary consideration given to model runtime.

![results table](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/house_price_results.png 'results table')

[Notebook](https://github.com/brianmcguckin/thinkful_unit_03_capstone/blob/master/unit_03_capstone_final_notebook.ipynb), [Slides](https://github.com/brianmcguckin/thinkful_unit_03_capstone/blob/master/slides_housing_price_capstone.pdf)

**Topics:** data preprocessing, visualization, feature engineering, machine learning, regression

**Toolkit:** Python, Jupyter, NumPy, Pandas, Matplotlib, Seaborn, SciPy, SKLearn, XGBoost

## Reuters-21578 Text Classification
This is an NLP focused project tasked with utilizing unsupervised learning methods to classify topics for  articles in the [Reuters-21578 Dataset](https://archive.ics.uci.edu/ml/datasets/reuters-21578+text+categorization+collection). After the articles were loaded, cleaned, and classes inspected, two subsets of the data were used to form a binary class set as well as a three class set. The words were then vectorized using tf-idf and clustering algorithms were given a chance to categorize the articles, using both Latent Semantic Analysis (LSA) and Uniform Manifold Approximation & Projection (UMAP) dimension reduction techniques. While the results were mostly poor, spectral clustering showed some promise with the right parameters. Then supervised classifiers performed the same task, which much more success even in untuned vanilla form.

![alt text](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/nn_clusters.png 'spectral clustering nearest neighbors')

![alt text](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/nlp_xgb.png 'xgboost results')
![alt text](https://raw.githubusercontent.com/brianmcguckin/brianmcguckin.github.io/master/images/nlp_logregr.png 'logregr results')

[Notebook](https://github.com/brianmcguckin/thinkful_unit_04_capstone/blob/master/04_capstone_unsupervised_learning_final.ipynb)

**Topics:** text cleaning, tokenization, vectorization, dimensionality reduction, machine learning, clustering, classification

**Toolkit:** Python, NumPy, Pandas, Matplotlib, Seaborn, NLTK, SciPy, SKLearn, XGBoost, RegEx, UMAP
