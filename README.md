## Heart Disease Prediction 

A Logistic Regression Model trained on [Kaggle's Heart Disease Dataset](https://www.kaggle.com/datasets/krishujeniya/heart-diseae)

### Project Overview

Cardiovascular diseases are a leading cause of death worldwide. This project aims to develop a simple yet effective model to predict heart disease, helping in early detection and prevention. By analyzing key health indicators such as age, cholesterol levels, etc., this model can classify whether a patient is at risk of heart disease.


### Contents

- `Exploration.ipynb`: A Notebook dedicated to data exploration and preprocessing.

- `LogisticRegression.ipynb`: The Notebook where the Logistic Regression is trained over the clean data.

- `XGBoost.ipynb`: The Notebook containing Extreme Gradient Boost model trained over the clean data

- `requirements.txt`: A file listing the Python dependencies needed to run the notebooks.

- `heart-disease.csv`: The dataset file over which the model is trained.


### How to Run 

1. Clone this repository

2. Install dependencies 

3. Run the notebooks.


### Model Performance 

1. For **Logistic Regression**:
```
              precision    recall  f1-score   support

           0       0.85      0.83      0.84        41
           1       0.86      0.88      0.87        50

    accuracy                           0.86        91
   macro avg       0.86      0.85      0.86        91
weighted avg       0.86      0.86      0.86        91
```


2. For **XGB Classifier**:
```
              precision    recall  f1-score   support

           0       0.88      0.85      0.86        41
           1       0.88      0.90      0.89        50

    accuracy                           0.88        91
   macro avg       0.88      0.88      0.88        91
weighted avg       0.88      0.88      0.88        91
```

### Future Work 

This project can be extended by exploring more advanced models to improve its accuracy. Regarding Random Forest, I could achieve Max accuracy upto 0.802, which is actually lower than that of Logistic Regression (0.86); perhaps more work need to be done to search for better data and preprocessing.


### Contributing 

Contributions are welcome! Feel free to make pull requests.


### License 

The data used in this project is licensed under [MIT License](https://www.mit.edu/~amini/LICENSE.md).