# PROJECT TITLE 
Predicting incident priority based on selected attributes


## ABOUT THE PROJECT
This project shows us how to predict priority of an incoming incident based on several key attributes of the incident.
This is particularly useful in IT service industry which relies mostly on service and maintenance of software applications
Being able to predict the priority of incidents based on particular attributes can significantly increase the predictability and resource allocation, which can lead to better resolution time.

## DATA
https://archive.ics.uci.edu/ml/datasets/Incident+management+process+enriched+event+log
Amaral, C. A. L., Fantinato, M., Reijers, H. A., Peres, S. M., 
Enhancing Completion Time Prediction Through Attribute Selection. 
Proceedings of the 15th International Conference on Advanced Information Technologies for Management (AITM 2018) and 13th International Conference on Information Systems Management (ISM 2018), 
Revised Selected Papers â€“ Lecture Notes in Business Information Processing, v. 346, pp. 3-23, 2019. [Web Link] 

## MODEL 
I used Gradient Boost classifier. Since the data I was using had high bias towards Medium priority incidents, the gradient boost mechanism helps. 

## HYPERPARAMETER OPTIMSATION
I tried to optimize two important parameters, learning_rate and n_estimators. 

## RESULTS
The basic model with default parameters provided a score of 81.36%
However, hyper-parameter tuning approach did not work as expected and after a few attempts, I could only achieve 79% accuracy. I need to work more on this.
