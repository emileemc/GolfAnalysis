
Data Analysis – 
1.	Data Cleansing and Descriptive
2.	KMeans Clustering – Exploratory analysis
3.	Variable selection 
4.	Model creation
5.	Validation – ROC curve
6.	Recommendations

1. DESCRIPTIVES 
First step in the data analysis is to make sure our assumptions are true including normal distributions and multicollinearity
•	In further description and understanding, gender was 42% female and 58% male, a rather close division. 
•	Marital status included 68 married, 17 divorced, and 15 single. 
•	This gives a greater understanding of the dataset and the observations. In these histograms, there are normal distributions. This characteristic of the data is valuable for moving forward with any further analysis. 
Below is a visual description of four key variables and their distributions                  

Multicollinearity


 

2. KMeans CLUSTER
•	This test is another way to better understand the data and utilize it to the fullest
•	While this is not a part of the churn model analysis
•	Customer Segmentation
•	Group 2 has a much higher average Membership Years and Group 7 has a much higher average commute distance and low membership years

 











3. VARIABLE SELECTION	
Boosting is used choose the important variables that the logistic regression outcome defines as significant while the decision tree gives further insight into the variables. 
•	Gradient Boosting uses the depvar =Churn
•	Includes all predictors in the dataset to narrow down which variables to include in the logistic regression and decision tree
•	The data mining technique of boosting is a fairly new method that has grown rather popular in marketing research and data analysis. 
•	This method of boosting works by applying weights to variables that are more impactful in predicting the outcome of the churn binary variable.
 
Chosen variables: 
Predictor Variables	Definition
Membership Years	Total Years the customer has been a member at the club.
Yearly Income	in thousands
Commute Distance	commute distance to the golf club
Dinner Purchases 	Total amount in dollars of dinners purchased in last six months


4. CHURN MODEL - DECISION TREE AND LOGISTIC REGRESSION
Outcome of the decision tree:
•	Dinner is the root node and can be interpreted:
o	46% churn while 54% do not – total of 100% of the dataset
o	96% of passengers do not churn if dinner purchases are above $308 in past 6 months
•	If dinner purchases are less than $308 and yearly income is less than $125,000 than 90% will churn
•	If dinner purchases are greater than or equal to $308 than 10% chance of leaving
•	If you look at the color coding the blue are the more likely to churn and green is less likely

 


LOGISTIC REGRESSION

Dinner	Commute  Distance	Total  Children	Vacation   Home	Gender	Membership  Years	Churn	prob
0	36	1	Y	F	2	1	0.662
0	18	4	Y	F	5	0	0.661
0	21	2	Y	F	6	1	0.659
0	33	1	Y	F	15	1	0.659
0	31	4	Y	F	15	0	0.659
0	27	4	Y	F	3	0	0.658
0	10	2	Y	F	1	1	0.658
0	37	1	Y	M	11	0	0.658
0	7	2	Y	F	6	1	0.657
0	42	4	N	F	5	0	0.657
5. VALIDATION
•	A ROC Curve was used to assess the performance of the model
•	AUC was 0.69 for the decision tree and 0.64 for the logistic
•	Marketing models with an AUC of 0.70 are often considered very reliable models

 



6. REVENUE LOSS AND MARKETING BUDGET ALLOCATION BECAUSE OF CHURN
•	In preventing the customer churn for the golf clubs, this will save the club any loss of related revenue. It is approximately $10,000 annually per 1 customer. That can be in upward revenue of $100,000 for certain clubs who lose 10 members a year. 
•	With a potential loss of revenue of this amount, placing marketing strategies in place would be increasingly important and save any potential loss in revenue with the right campaigns in place. The marketing budget can be allocated accordingly with placing importance on certain variables and formulating campaigns to target the audiences in risk of leaving.














