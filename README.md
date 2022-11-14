# my_portfolio
Example data science portfolio

## [Project 1: Classifier](https://github.com/JJSSEE/my_portfolio/blob/main/notebooks/Parkinson's%20Disease.ipynb)

## Parkinson's Desease Detection

### Labels count
* Target label, given in binary numbers with a healthy status of zero (0) and a desease status of one (1).

status - Health status of the subject (one) - Parkinson's, (zero) - healthy
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* Built a client facing API using flask 

![](https://github.com/JJSSEE/my_portfolio/blob/main/images/label_count.png)


### Confussion Matrix
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 


![](https://github.com/JJSSEE/my_portfolio/blob/main/images/heat_map.png)

### Area Under the Curve

For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

![](https://github.com/JJSSEE/my_portfolio/blob/main/images/roc_auc.png)

