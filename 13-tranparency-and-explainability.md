# Transparency and Explainability

## Transparency

1. Definition: the characteristic represents the internal decision-making processes visible and interpretable
2. Key points:
   1. the underlying decision-making process is understood
   2. involve simpler models and linear regression
   3. easy to debug and modify
3. Advantages:
   1. high accuracy
   2. high trust and deployment in regulated industries

## Explainability

1. Definition: the characteristic represents the possibility to explain the model's output in human-understandable terms
2. Key Points:
   1. irrelevant to model's complexity, the explanation of the model's output still can be applicable
   2. black-box models' output can be explained as well
3. Advantages:
   1. useful for complex non-linear models
   2. ensures Transparency

## Model Safety

1. Definition: The characteristic that ensures expected behaviour without causing an unintended harm
2. Focus Area: bias, ethical concern, harmful output
3. Why it Matters: Gen AI are high stakes when generates sensitive information

## Trade-off

Model Type|Pros|Cons
-|-|-
Transparent|Easier to trust, debug, deploy in regulated industries|Performance lack of complex models
Non-Transparent|High accuracy for complex tasks|Lack of interoperability and understanding
Safe|Intended outout|Reduce the model's performance

## AWS Transparency and Explainability Tools

1. AWS SageMaker Model Card
   1. It documents critical details of machine learning
   2. Version control controls information about the model throughout its lifecycle
   3. It provides model overview, intended uses, risk rating, metrics evaluation, training details
   4. It supports audit, insights on model behaviour
   5. Risk Rating

### Model Card Risk Rating

#### Purpose

1. Indicate if model is suitable for the use-case based on its training data, performance and assumptions
2. Assist in model governance, providing potential biases, data limitations
3. Highlights future testing, monitoring, and mitigation strategies before deployment

#### Categories

1. Low Risk - the model is safe for the intended use case. Example, well-tested recommendation model for a non-sensitive e-commerce site
2. Medium Risk - the model is suitable for most use cases, but there are concerns of its performance or fairness. It requires further monitoring and evaluation. Example, the model, that predicts company rotation, that has been trained on limited data
3. High Risk - the model has biases, or accuracy, etc. It must not be deployed until further development. Example, facial recognition
4. Unknown - there is not enough information to determine the risk level, which happens due to lack of testing, or uncertain data. Example, newly developed model, experimental dataset
