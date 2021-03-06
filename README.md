# Devising-Predictive-Models-to-identify-potential-caravan-mobile-home-policy-owners
The primary goal of this project was to apply different algorithms and methods to analyze if customers are interested in the caravan insurance policy. This would depend on whether there are any factors which will help in classifying customers as either being interested or not being interested in purchasing this insurance. Getting to this point involved data cleansing and exploratory analysis which helped in understanding the demographics and decide on how the data needs to be used.


This was a highly dimensional and unbalanced dataset since the number of variables was 86 and the number of people who actually got the insurance was very less when compared to people who did not have the insurance. Measures like finding the correlation to remove some variables and undersampling/oversampling were taken to get rid of the high dimensionality and unbalance.
Once this was established, further analysis of uncovering patterns in data using predictive techniques followed. The models were implemented for the original dataset as well as the undersampled and oversampled data. We assumed that currently the organization is targeting all kinds of customers and the cost to acquire a customer is insignificant. Employing a targeting strategy based on the models using undersampled and oversampled data, would prove more profitable since this will lead to getting more purchases by approaching less number of people.

CONCLUSION

Bagging achieves the best sensitivity while Random Forest has better precision. Still, Naive Bayes seems to be the best model for our study since it has a balance between both sensitivity and precision. It still has low precision but that should not pose a huge problem because of our assumption of cost for attempting to acquire a new customer not being very high.
Targeting would prove to be a profitable approach since these models will let the organization have a strategy in place. Targeting all kinds of customers is counterproductive and does not generate the right kind of results.
These models will help in generating leads which would mean the firm will aim for a smaller set of people but still be able to get more customers out of them when compared to the previous strategy.
