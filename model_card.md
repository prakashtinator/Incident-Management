**Input:** There 9 features and one output variable selected for this model. 

**Output:** The model predicts the priority of incident based on the selected features

**Model Architecture:** I have used a gradient boost classifier. 

## Performance

The basic model with default parameters provided a score of 81.36%
However, hyper-parameter tuning approach did not work as expected and after a few attempts, I could only achieve 79% accuracy. I need to work more on this.

## Limitations

The model needs the categorical data to be encoded numerically. This can cause confusion for the ML models.

## Trade-offs

The grid search is pretty resource extensive. This causes time consuming hyper-parameter tuning.