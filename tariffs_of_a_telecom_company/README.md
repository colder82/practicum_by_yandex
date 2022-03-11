## Data

Data about two tariff plans of a federal mobile operator is provided in 5 files:

calls.csv (information about calls)
- unique call number 
- call date 
- call duration in minutes
- user id,

internet.csv (information about Internet sessions)
- unique session number 
- the amount of Internet traffic spent per session in Mb 
- internet session date
- user id,

messages.csv (information about messages)
- unique message number 
- message date
- user id,

tariffs.csv (information about tariffs)
- tariff name 
- monthly subscription fee in rubles 
- number of minutes per month (included)
- number of messages per month (included)
- internet traffic volume (included)
- the cost of a minute above of the tariff package
- the cost of a message above of the tariff package
- the cost of 1 Gb above of the tariff package,

users.csv (information about users)
- user id 
- first name 
- last name
- age
- registration date
- tariff termination date
- city of residence
- tariff name.

## Task

Need to understand which tariff brings in more money in order to adjust the advertising budget.

Test hypotheses:
1. The average revenue of users of the Ultra and Smart tariffs is different.
2. The average revenue of users from Moscow differs from the revenue of users from other regions.

## Libraries used
*pandas*, *matplotlib*, *seaborn*, *scipy*, *numpy*
