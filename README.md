Lending Club Case Study Write-Up

Please see IPython Notebook for further details including visualizations and code.


Part I:

Looking at the data descriptively, B and C grade loans seem to be the most prominent with less emphasis being placed on higher risk, subprime lending. Histograms of the loan grades and trended views on the number of loans by grade demonstrate this.

As a result, the average interest rate across all loans is 13.3 %  with a standard deivation of 4.4.

Part II:

We assume that rate of return can be calculated as (total payments - principal)/principal where the total payments includes all payments made by the borrower including interest payments and fees.  For simplicity, we do not consider the time value of money in our calculation.

The average rate of return across all mature short-term loans is 8.2%.  Looking at returns trended over time, LC returns improved dramatically in 2009 and peaked in 2012.

When segmented by year and loan grade, we see that G grade loans in 2012 were the most profitable with returns of 18.8%.

Part III:

Here we build several models that predict the returns of LC 36 month loans.  We test model accuracy by comparing each model against one another and by measuring Root Mean Squared Error (RMSE), a statistical measure of accuracy, for each model.

Ultimately, the simple decision tree model with 5 levels proved to be the most accurate with an RMSE of 0.237.

I chose this model primarily for its interpretability and relatively low computation times. A decision tree produces very intuitive findings that businesses can quickly execute upon and is therefore preferred when creating models that influence decision-making.

As a next step, I would include categorical dummy variables in the model to see if model accuracy can be improved. Additionally, I would attempt other unsupervised learning models such as logistic regression to improve predictions.






