
# Welcome to the Credit Card Fraud Detection project.

![image](https://image.slidesharecdn.com/creditcardfrauddetection-140719133724-phpapp01/95/credit-card-fraud-detection-1-638.jpg?cb=1405778467)

## Objective

The main objective is to find a model that classifies me the frauds and non-frauds of our [dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) . To be able to avoid the least amount of false negatives and false positives because we don't want our model to be unable to predict fraud or people who didn't commit fraud to have inconveniences.

## Development

In the file Fraud_Detection.ipynb will show the step by step of the creations of the models but before running that file you have to follow these steps:

```bash
!git clone https://github.com/julieta77/Credit_Card_Fraud_Detection
!cd Credit_Card_Fraud_Detection
!python -m virtualenv your_venv
!your_venv/Scripts/activate
!pip install -r requirements.txt
 
```

## Conclusion

With the predictions obtained from the 5 classification models we can see the three best models that come close to our goal. The first is neural networks with an f1-score of 0.79. Then it is LinearSVC with an f1-score of 0.76. Finally it is DecisionTreeClassifier with a 0.73 of f1-score.

