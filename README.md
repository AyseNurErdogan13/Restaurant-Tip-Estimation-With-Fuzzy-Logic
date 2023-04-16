# Restaurant Tip Estimation With Fuzzy Logic
 This project uses fuzzy logic to predict what percentage of tip a customer is likely to give based on the quality of food and service they receive.
## Inputs

- Service Quality: A number representing how good the waiter's service is (0-10).
- Food Quality: A number representing how tasty the food is (0-10).
## Outputs

Tip Percentage: A number representing what percentage of the bill the customer is likely to tip (%0 - %25).
## Fuzzy Sets

Inputs and outputs are evaluated using the following fuzzy sets:

- Service Quality: Poor, Acceptable, Great
- Food Quality: Bad, Okay, Delicious
- Tip Percentage: Low, Medium, High
## Rules

The following rules are used to predict the tip percentage:

- If the service is great and the food is delicious, the tip will be high.
- If the service is acceptable and the food is okay, the tip will be medium.
- If the service is poor or the food quality is bad, the tip will be low.
## Project Files

- FuzzyLogic.ipynb: A Python script that uses fuzzy logic to predict the tip percentage.
- README.md: This file.
