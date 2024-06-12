# suicide prediction using socioeconomic factors

Mental health and suicide have become increasingly prevalent global concerns, prompting initiatives such as the World Health Organization's "Mental Health Action Plan" to address rising suicide rates. One contributing factor is the correlation between socioeconomic status (SES) and mental health issues leading to suicide. Individuals from lower socioeconomic backgrounds often face heightened risks, exacerbated by factors like financial strain, job insecurity, and societal pressures.

To tackle this pressing issue, companies, healthcare agencies, and communities can implement various initiatives, including counseling services, crisis hotlines, and workplace flexibility. By leveraging predictive models built on comprehensive datasets, organizations can gain insights into suicide rates across different countries and years, enabling targeted interventions and support systems.

## Dataset
The dataset used in this project explores worldwide suicide trends from 1990 to 2022, sourced from Kaggle. It includes data on suicide rates, demographic information (region, country, year, gender), and economic indicators (GDP, GDP per capita, GNI, GNI per capita, inflation rates, employment-to-population ratios).

## Code Overview
To address the socioeconomic status and suicide rates prediction problem, the following steps were taken:

### Data Preprocessing:
Null values were handled using mean imputation, and data patterns were visualized through pairplots and correlation plots.

### Modeling: 
Both classification and regression models were employed, including logistic regression, decision tree classifier, random forest, boost tree model, KNN neighbor, Naive Bayes for classification, and multiple linear regression for regression. Deep learning models such as ANN Classifier and Keras Classification were also implemented.

### Model Evaluation: 
Model performance was assessed using ROC AUC curve, classification reports, confusion matrices, and training/validation loss for deep learning models.

## Dataset Source
Global Suicide Rates 1990 to 2022
(https://www.kaggle.com/datasets/ronaldonyango/global-suicide-rates-1990-to-2022)


## Reference
Mental Health Action Plan
(https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5463019/)
Feel free to clone this repository and explore the code and findings further. If you have any questions or feedback, please don't hesitate to reach out!
