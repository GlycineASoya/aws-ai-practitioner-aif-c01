# ML Model Performance Metrics

## Metrics

1. Accuracy = Correct Predictions/Total Number of Predictions ((TP+TN)/(TP+TN+FP+FN))
2. Presicion = True Positive Predictions/(True Positiv + False Positive) (TP/(TP+FP))
3. Recall (Sensivity) (TRP - True Positive Rate) = True Positive Number/(True Poisitives + False Negatives) (TP/(TP+FN))

## Scores

1. F1 score - Precision and Recall mean
   1. use-case: detect class distribution imbalance (detecting rare events)
   2. use-case: an additional metric if different penalties for False Positive and False Negatives
   3. use-case: an additional metric if Precision or Recall scores alone are not sufficient
2. Area Under the ROC Curve (AUC-ROC) - the metric of classification model, describes False Positive likeliness. **The higher, the better model**.
   1. value 0.5 - straight line, model random guessing
   2. value 0.67 - moderate model
   3. value 0.9 - optimal model, minimum False Positives
3. Mean Squared Error (RSE) - the metric of regression models, represents the sum of squared values of difference between the prediction and actual value for  the observation time. **The closer to 0, the better**
4. R-Squared - the metric of regression models, represents proportion of the variation in the dependent variable, predictable from the independent variable. **The closer to 1, the better model, the closer to 0, the worse model**. Shows how well the model fits the data
