# Predicting Customer Engagement to Insurance Company Marketing Campaign
## Project Summary
This project aims to use descriptive analysis to draw insight into customer behavior and factors that drive customer engagement rate to the marketing campaign of the insurance policies. 
## Data Analysis and Visualization
This is to take a more detailed look at the data to understand better what data points we have and what pattern we can see.
### Engagement rate
![engagement.png](engagement.png)
- About 14% of the customers responded to marketing campaign calls, and remaining 86% of the customers have not responded

### Sales Channels
![channels.png](channels.png)
The above table helps visually explain the distribution between the engaged and non-engaged in each sales channel. About half of the engaged customers were from agents, whereas non-engaged customers are more evenly distributed across all four channels.
### Engagement by Coverage
![engaged1.png](engaged1.png)
![engaged2.png](engaged2.png)
There is an even distribution of engaged and non-engaged based on Coverage. 61% of the customers that engaged comes from customers signed up for basic premiums 

### Total Claim Amounts
![claims.png](claims.png)
The above boxplots show the distribution of the Total Claim Amount between the engaged and non-engaged groups
## Prediction
This involve using logistic regression model to understand the patterns of behavior between the engaged group and non engaged customers
### Regression Analysis
![regression.png](regression.png)
From the output of the above model, the Income, Monthly Premium Auto, Months Since the Last Claim, Months Since Policy Inception, Number of Open Complaints, Number of Policies and Gender variable are significant at 0.05 significant level. And all of them have negative relationships with the engagement. Hence, the higher the income, the less likely it is that customers will be engaged with marketing calls. Similarly, the more policies that the customer has, the less likely that they will be engaged with marketing calls. Lastly, the male gender is less likely to engage with marketing calls than female customers.
