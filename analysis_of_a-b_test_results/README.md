## Data

Data of a large online store is provided in 3 files::

hypothesis.csv (hypothesis)
- brief description of the hypothesis
- user coverage on a 10-point scale
- impact on users on a 10-point scale
- confidence in the hypothesis on a 10-point scale
- efforts for hypothesis testing on a 10-point scale,

orders.csv (A/B test order data by day)
- order (transaction) id 
- id of the user who made the order
- order date
- revenue
- the A/B test group the order is in,

visitors.csv (data on the number of A/B test users by day)
- date
- the A/B test group 
- number of users.

## Task

1. Prioritize hypotheses with ICE and RICE frameworks;
2. Analyze the results of the A/B test.

## Libraries used
*pandas*, *matplotlib*, *seaborn*, *scipy*, *numpy*
