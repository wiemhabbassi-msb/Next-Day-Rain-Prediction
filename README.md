# Next-Day-Rain-Prediction
# Rain in Australia: Will It Rain Tomorrow?

Machine learning project that predicts whether it will rain the next day in Australia from daily weather data.

## About

- **Goal:** predict `RainTomorrow` (Yes/No) from today's weather
- **Data:** `weatherAUS.csv`, 145,460 daily records, 49 locations, 2007 to 2017
- **Challenge:** only 22% of days are followed by rain (unbalanced target)

## What We Did

- Cleaned the data and handled missing values
- Selected the 10 most informative features
- Balanced the training set with undersampling
- Compared 5 models: Logistic Regression, SVM, Decision Tree, Random Forest, Gradient Boosting

## Results

- **Best model:** SVM with AUC 0.86
- Catches 77% of rainy days
- Strongest predictor: humidity at 3pm

## Files

- `rain_project.ipynb`: full code and analysis
- `weatherAUS.csv`: dataset
- `Rain_Prediction_Presentation.pptx`: project presentation

