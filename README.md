# MASSP Project

## Task

- Predict house prices in Ames, Iowa using 79 variables and price of sold houses.

## Dataset

- Consist of 4 files:
  + **train.csv**: include data with 79 features and sale prices of 1460 sold houses. 
  + **test.csv**: using model trained with **train.csv** to predict prices of 1459 houses in this file.
  + **sample.csv**: include the format for our submission and sample results

## Approach

- Data cleaning:
  + Eleminate column that don't affect house prices (having the same value or null with all rows)
  + Numberic values (in case the value is null, replace it with 0)
  + Create new variables which could possibly be associated with our outcome
  
- Data exploration:
  
