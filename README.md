# Cardiovascular-Risk-Prediction

## Introduction
**The heart is one of the main organs of the human body. The heart plays the most crucial role in the circulatory system. If the heart does not function properly then it will lead to serious health conditions including death.  Cardiovascular diseases (CVDs) are the leading cause of death globally, according to WHO, an estimated 17.9 million people died from CVDs in 2019, accounting for 32% of all global fatalities. Though CVDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and in some cases, even death.
As a result, it is critical that we accurately predict the risk of heart disease in order to avoid as many fatalities as possible.**

## Steps involved

* **Data Preparation**
* **Exploratory Data Analysis**
* **Data Preprocessing**
* **Machine Learning Model Implementation**
* **Model Explainability**
* **Conclusion**

## Conclusion
Predicting the risk of coronary heart disease is critical for reducing fatalities caused by this disease, we can avert deaths by taking required medications and precautions if we can foresee the danger of this illness ahead of time.


* It is important to have a high recall score in this scenario because It is okay if the model incorrectly identifies a healthy person as a high risk patient, because it will not result in death, but if a high risk patient incorrectly identified as healthy, it may result in fatality. **Support Vector Machine with rbf kernel is the best model with recall score of 0.88**.


* There may be a case where the patients who are incorrectly classified as suffering from heart disease is equally important as patients who are correctly classified as suffering from heart disease, because patients who are incorrectly classified they may have some other illness, so in that case high f1 score is desired. **Logistic Regression, XGBoost, K-NN these are the model with most F1 score.**

* From our analysis, it is found that the **'Age'** of the patient is the most important feature in determining the risk of coronary heart disease, middle and older age people are more prone to coronary heart disease than younger people  followed by **'cigarettes per day'**,  **'BP Meds'**, **'Prevalent Hypertension'** are also very important feature in determining risk of heart disease.

* Future developments must include a strategy to improve models scores with the help of more data from people with different medical history.
