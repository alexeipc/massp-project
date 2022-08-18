# MASSP Project

## Task

- Predict house prices in Ames, Iowa using 79 variables and price of sold houses.

## Dataset

- Consist of 4 files:
  + **train.csv**: include data with 79 features and sale prices of 1460 sold houses. 
  + **test.csv**: using model trained with **train.csv** to predict prices of 1459 houses in this file.
  + **sample.csv**: include the format for our submission and sample results

## Code:
https://colab.research.google.com/drive/1lbmSpA0KSon8F_oVR2Q0Hd84cGwOFZ03#scrollTo=rOanmB0Feen5

## Score review
| Model      | Score |
| ----------- | ----------- |
| Random Fores Regressor     | 0.14676       |
| Ridge   | 0.13691        |
| Gradient Boosting Regressor   | 0.13331        |
| BayesianRidge   | 0.13288        |
| LGBM egressor   | 0.13148        |
| Cat Boost Regressor   | 0.12458       |
| Mix model (0.25 - 0.1 - 0.1 - 0.25 - 0.3)   | 0.12446        |
| Mix model (0.2 - 0.2 - 0.2 - 0.2 - 0.2)   | 0.12443        |


  
