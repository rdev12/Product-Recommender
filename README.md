# Introduction
An e-commerce company wants to recommend products to its users. The company has collected only transaction data in the past. The training dataset has only 3 columns - user_id, Product bought and Order value of the product. Using this dataset, predict for all the users in the training dataset, the top 3 categories that the user might buy from.

The details of the competition can be found here: [Univ.AI](https://hack.univ.ai/hackathon/2)

The Kaggle notebook can be found here: [Notebook](https://www.kaggle.com/rdev12/product-recommender)

# Data
"user_id": id associated with a user 
"product bought": the category of the product bought by the user
"order value": the money spent on the product 

# Dependencies
- numpy
- pandas
- seaborn
- matplotlib
- sklearn
- pandas_profiling

# Installation
  ```
  pip install numpy
  pip install pandas
  pip install seaborn
  pip install matplotlib
  pip install scikit-learn
  pip install pandas-profiling
  ```

# Model
The model involves finding appropriate threshold for each category of product and applying a XGB classifier to predict the overall top 3 product category.
Also, the data is resampled to alleviate the class imbalance

# Results
The best submission of my model got a rank of 34 
