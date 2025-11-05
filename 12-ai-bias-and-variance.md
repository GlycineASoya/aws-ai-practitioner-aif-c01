# AI Bias and Variance

## Bias

1. Definition: The error introduced by approximating a real-world problem with a simplified model
2. Sources:
   1. Training Data Bias: incomplete data misrepresents certain demographic groups
   2. Algorithmic Bias: the design of the model or the decision-making process leads to biased outcome
3. Impact:
   1. Inaccurate predictions
   2. Demographic Disparities
   3. Ethincal Concerns

### AWS Bias Mitigation Tools

1. AWS SageMaker Clarify
   1. Detects and mitigate bias in ML Models BEFORE deployment
   2. Detects data skew and bias during training
   3. Provides decision-making insights
   4. Monitors models in production for fiarness and transparency
2. AWS SageMaker Model Monitor
   1. Monitors accuracy and performance of the model
   2. Tracks model drift
   3. Notifies users of deviations
   4. Captures metrics without manual setup
3. Amazon Augmented AI (A2I)
   1. Integrates human reviews into model
   2. Involves human reviewers to verify model predictions
   3. Faster deployment with out-of-the-box solutions
   4. Different areas of application (healthcare, finance, etc)

## Variance

1. Definition: The error introduced by the model's sensisvity to small fluctuations in the training dataset
2. Sources:
   1. Overfitting: the model consumes not training data only, but the noises and outliers
   2. Model Complexity: complex models with too many parameters tend to have high variance
3. Impact:
   1. Inaccuracy: the trained model performs bad on the new data
   2. Underfitting: fails to capture underlying patterns
