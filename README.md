# Knight_Fintech_assignment
Summary:
The training dataset contained around 82K instances. Dataset was inspected for any NaN values. Many such values were found.
To deal with it, various techniques were used. The username column was dropped. The price nan values were filled with mean values
of price coloumn. Other categories were not removed. they were just filled by Unknown. This would help the data maintain its
features by just adding another category named Unknown.
Then Visualization of the data was performed to develop an understanding about the dataset and observe any trends.
NLP was performed converting the review description into vectors and then training. 
Review title and review description and othercombinations were used to predict varities of wine. 
Finally review description was chosen for predicting wine categories as no other feature could predict variety of wine.
Models Used and accuracies obtained on training dataset:
Linear SVC:           89 % 
Naive-Bayes:          50 % 
SGDC:                 74 %
Logistic Regression:  78 %

5 Actionable Insights:

1. The most number of wine were tasted by country U.S. That means increasing production and focusing on more on the quality can help increase profits.
2. The average points provided by the people of England were highest.
3. The average price is higher in Switzerland.
4.  The producer of top 20 wines are France taking a share of 50%,then U.S.(25%),Italy(20%), Portugal(5%) . So focusing more on these will help earning more profit.
5. The mean points obtained overall by the reviewers were 88.54 which should be improved as the lowest rating was 80 and highest 100. 


