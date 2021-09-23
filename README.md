# This is a demonstration of how I work
This challenge was carried out as part of the application process for a Data Scientist position at Mercado Libre. I solved it successfully and joined the company!

## Challenge description:
- Get data from Mercado Libre's API
- Perform an Exploratory Data Analysis (EDA)
- Solve business questions: What is the average discount in each category of the marketplace? How many televisions are discounted? And how many cellphones?
- Develop a model for predicting product sales
- Analyze it's results

## My work: 
- Everything is contained in 1 file as required (readability will not be the best)
- I developed custom made classes & functions to get data from Mercado Libre's API
- Pipeline for data preprocessing
- EDA on raw data:
  1. On raw data: How much missing data do we have in each feature? 
  2. On raw data: How much missing data do we have for each customer?
- Answered business questions
- EDA on preprocessed data
  1. Correlation matrix 
  2. Univariate analysis (not showed for simplicity)
  3. Bivariate analysis
- Raw model
- Hyperparameter tuning (gaussian search)
- Pipeline tuning
- Model results
- Quick error analysis
- Explainability using SHAP

It is a long notebook and I did not delve into all the points, because this was just a demonstration of how I work.
Model selection: I chosed RandomForest for simplicty, but I would not do that for predicting sales because tree-based models don't extrapolate their predictions.
And, eventually, sales will exceed the training set limits.

