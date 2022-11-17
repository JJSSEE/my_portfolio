# my_portfolio
Example data science portfolio

## [Project 1: Classifier](https://github.com/JJSSEE/my_portfolio/blob/main/notebooks/Parkinson's%20Disease.ipynb)

## Parkinson's Desease Detection
Parkinson’s disease is a progressive neurodegenerative disorder of the central nervous system. The cause of the desease is unknown and there is no cure. A dataset containing information of healthy patients and patients with the desease is analyzed, and three different classification algorithms were used to detect the presense of the desease.
* Random Forest
* Logistic Regression
* XGBoost

### Target Variable
* Healthy status of zero (0) and a desease status of one (1).
* Data size characterized by being small and umbalanced.

![](https://github.com/JJSSEE/my_portfolio/blob/main/images/label_count.png)


### Confussion Matrix

* Train and test data was split at the ratio of 80/20.
* All three models identified the health status of all the patients correctly.

![](https://github.com/JJSSEE/my_portfolio/blob/main/images/heat_map.png)

### ROC and AUC Matrics

* Data dimentionality was reduced by removing low variance features 
* The trainning data is overffited and it is expected given the small size of the dataset


![](https://github.com/JJSSEE/my_portfolio/blob/main/images/roc_auc.png)

## [Project 2: Regressor](https://github.com/JJSSEE/my_portfolio/blob/main/notebooks/Superconductivity_project.ipynb)

## Superconductivity critical temperature prediction

![](https://github.com/JJSSEE/my_portfolio/blob/main/images/download.png)

![](https://github.com/JJSSEE/my_portfolio/blob/main/images/sup_heat.png)



