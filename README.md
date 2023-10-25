<p align="center">
  <img src="/images/Logo-personal_Fondo_blanco.png" alt="Logo_personal">
</p>

<div align="center">
  <h1 align="center">Credit card fraud predictive model</h1>
  <h2 align="center">Decision tree - Random forest</h2>
</div>

## Introduction
This project is aimed at generating a predictive model of credit card fraud using the decision tree algorithm and random forest. Registers are used with variables from the transaction and the card record

The work is carried out based on analysis, compression, data cleaning, metrics, exploration, testing and validation of the model, with the following work path:

- Development
- Understanding the data
- Data cleaning
  - Check null values
- Exploratory data analysis
  - Correlation matrix
  - Outlier detection
  - Data standardization
  - Split training, testing and validation data
- Predictive model - Decision tree 
  - Create and train the model
  - Model evaluation
  - Evaluate the model with cross validation
  - Check feature importances
  - Impact of maximum depth
- Predictive model - Random Forest 
  - Create and train the model
  - Model evaluation
  - Impact of maximum n_estimators on the model
- Demonstration of model classification
- Conclusions

## Data
The de kaggel dataset ["Credit card fraud"](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud), contains medical records whether the breast cancer is benign or malignant. The characteristics are transaction data and card records with their respective label, whether it was a fraudulent transaction or not. 

**Attribute Information:**

* distance_from_home: The distance from the home where the transaction took place.
* distance_from_last_transaction: The distance from the last transaction made.
* ratio_to_median_purchase_price: Ratio between the purchase price of the transaction and the average purchase price.
* repeat_retailer: Was the transaction at the same retailer?
* used_chip - It is the transaction through chip (credit card).
* used_pin_number: Was the transaction made using the PIN number?
* online_order: Is the transaction an online order?
* Fraud: Is the transaction fraudulent?

<p>
  <img src="/images/output.png" alt="Grafico readme">
</p>

