# Responsible AI

## Features

1. Bias
   1. Definition: Bias refers to a systematic favoritism or prejudice towards a specific group
   2. Why it matters: Biased AI makes inequalities persistent
   3. Solution: trace fairness metrics and use bias correcion techniques
2. Fairness
   1. Definition: Fairness ensures the AI outcome is equitable, especially for marginalized groups
   2. Why it matters: To avoid discrimination in AI areas
   3. Solution: Individual or Group fairness techniques
3. Inclusivity
   1. Definition: Inclusivity ensures underrepresented and disadvantaged groups are served by AI
   2. Why it matters: Increase wider accessability and avoid reinforcing inequalities
   3. Solution: diverse team, inclusive training data, considering the needs of all users during development
4. Robustness
   1. Definition: Robustness is the ability of AI systems to perform reliably under different conditions, as well as under adversarial attacks (the data the model consumes is intentionally manipulated)
   2. Why it matters: mkaing sure the AI systems are safe and dependable on real-world scenarios
   3. Solution:
      1. Adversarial Training: attempting Adversarial attacks to cause the model to expose a sensitive data or bias, AND
      2. Testing: testing under various conditions, edge cases
5. Safety
   1. Definition: Safe AI system prevents from generation of harmful outcomes
   2. Why it matters: misbehaving AI can lead to a catastrophic outcomes in critical areas, as healthcare, autonomous vehicles, etc.
   3. Solution:
      1. Predictability: the AI system should be transparent in decision-making (no black-box)
      2. Error Recovery: when error comes up the AI should gracefully fail
6. Veracity
   1. Definition: Veracity provides truthful, accurate and trustworthy information
   2. Why it matters: inaccurate AI outcome can lead to misinformation and misleading
   3. Solution:
      1. Data Integrity: using reliable and high-quality data
      2. Explainability: the decisions are clear for humans

## AWS Responsible AI Tools

1. AWS Bedrock Guardrails
