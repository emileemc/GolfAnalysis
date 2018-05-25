


Churn Prediction in Marketing for Membership Business and its Application
In an increasingly growing field of analytics it is important to remember the definition and roles of mathematical tests and statistical tests and outcomes. As many companies are becoming more aware of the data that they are able to collect, and the data they already have, they want to be able to maximize the benefits of all their data. These dashboards have grown, and will grow in many industries, but most recently there has been substantial growth in marketing. This study discusses the use of dashboards in marketing data analysis and application of the churn model to save revenue loss.
Researchers have found there are  wo goals in analyzing data. . . I prefer to describe as “management” and “science.” Management seeks profit. . . Science seeks truth. (Parzen, 2001). In this definition there is a combination of business management as well as the scientific purpose of finding the truth that creates sustainable marketing campaigns that allocate money efficiently and not just by chance without probabilistic determination. The emphasis on science and truth is important to understand that data application is meant to not only save revenue loss but also to positively impact communities which can be accomplished through the lens of psychology and social responsibility. 
It can be said there is a difference between one visualization that offers understanding, and one that offers prediction, and there are theories of social and human behavior addressing themselves to two distinct goals of science: (1) prediction and (2) understanding. It will be argued that these are separate goals [. . . ] I will not, however, conclude that they are either inconsistent or incompatible. (Dubin 1969). This really defines the difference between a statistical prediction dashboard and a dashboard used for summary and understanding, though both are important.  
In this study, the use of logistic regression was performed to predict customer churn on a sample of 100 customer profiles. Churn can be defined as a customer that has been inactive for the past 30 days including purchase of meals, tee times, and golf apparel. This new variable is utilized as the output variable in the logistic regression equation.
Through this study certain aspects of social responsibility are addressed in determining not only more profitable ways to bring customers to a business, but also to connect communities through shared interest. This perspective is shown to improve the triple bottom line of profit, people, and plant, as well as, making a positive change in communities through marketing. 
	In the application of the churn model, there will be a system that alerts the business owner of the customers that are in risk of leaving their membership. These results from the data are crucial to save the club a potential large revenue loss if a customer decides to leave their membership. This could be $100,000 annually for every thousand customers. 
The application will be proprietary visualization developed to inform marketing directors of better data-based decision making. There is more than one method to evaluate customer churn, including decision tree, support vector machines with CRM data with the ability to model nonlinear data (Farquad, Ravi, Raju 2014). It is also possible to combine tests including logistic regression and classification trees depending on the normalization of the data. For the purposes of this study, logistic regression will be used since the data is showing normalcy as well as multicollinearity not existing.
DESCRIPTIVES AND HYPOTHESIS
In the initial view of the data, there are several important frequencies to display to see the distributions of certain variables. In determining the appropriate hypothesis as well as understanding our dataset, commute distance, age, tee time purchases, and membership years are shown below.  In further description and understanding, gender was 42% female and 58% male, a rather close division. Marital status included 68 married, 17 divorced, and 15 single. This gives a greater understanding of the dataset and the observations. In these histograms, there are normal distributions. This characteristic of the data is valuable for moving forward with any further analysis. 
Below is a visual description of four key variables and their distributions.

 
Commute Distance	 
Age
 
Membership Years	 
Tee Time Purchase
From these distributions, a hypothesis can be created. The null hypothesis states the commute distance and tee time purchases have no effect on whether or not a customer will leave their membership. Churn prediction and its application will involve not only directly addressing the variables involved, but also offering incentives for the customer to stay, based on the newly created tee time variable that was created from historical purchases. The dependent variable will be a binary, nominal level variable of “Yes” or “No” coded as “1” or “0” respectively, which answers the question whether or not a customer has made a purchase in the last 30 days. The methodology behind this measurement is based on further marketing research including, the use of a prediction model to predict churners based on historical service usage information (Kim, Lee, & Johnson, 2013). With this strategy in place, the model is configured accordingly.
	Churn prediction consists of: (1) predicting which customers are going to churn and (2) evaluating which action is most effective in retaining these customers (Hung, Yen, & Wang, 2006). There are two tests used to evaluate the dataset this includes boosting, logistic regression, and decision trees. These methods are used simultaneously. Boosting is used crosscheck the important variables that the logistic regression outcome defines as significant while the decision tree gives further insight into the variables. The results of all three allow for a full picture of our churn variables. The decision tree highlights the specific variables while the logistic regression provides probabilities that are coherent with the decision tree’s output. 
NEWLY CREATED VARIABLES FROM POINT-OF-SALE DATABASE
	The absence of purchases for certain items defines the created variables “Tee Time All-time” and “Dinners All-time.” These variables are interval level measuring the total tee time and dinner purchases for each customer from January 2012- December 2014. These purchases were chosen because in being a member for a business there are always core reasons for that membership. For this case, playing golf or enjoying dinner are top priorities for these memberships. These purchases can be ranked higher in a qualitative assessment. If a customer purchases fewer of either of these items then there could be an issue. 
Quantitatively the analysis can go farther into these new variables. The logistic regression measures the significance of the variables and the customer's propensity to remain within the membership. If a customer only purchases $174 worth of tee times within the previous two-year time frame, their propensity to leave increases. Although this is not the churn measurement variable itself, it attributes greatly to the churn model, as it is an important variable for determining whether or not a customer will leave due to their lack of activity in the club. The application involves choosing the correct optimization and marketing strategies, which includes, those who are close to churn that have not purchased at least $174 worth of tee times in the past two years would receive a tee time discount, or another discount of what the customer has been purchasing. 
DATA AND PREDICTOR VARIABLES
	The dataset is a random sample of a national private golf club membership organization that includes Point of Sale purchases for two years (2012-2014) and a customer profile including demographics and length of membership. There are five nominal level variables, four ordinal level variables, and seven interval level variables. These 16 variables are all used to predict the churn binary variable. The dependent variable is whether or not the customer has made a purchase, including tee time in the past 30 days. 
	The variable “October Purchases” was chosen because of the seasonality of the data and the increase in sales during this peak season. There are a total of 100 observations in the sample of customer profiles, and 5,514 POS transaction observations including Customer ID, item purchases, date, and dollar amount of that purchase. The datasets were approached separately, then combined to form a more dynamic and higher dimensional view of the customer and their behavior. 
Predictor Variables	Definition
Membership Years	Total Years the customer has been a member at the club.
Marital Status	Married, Single, or Divorced
Gender	Male of Female
Yearly Income	in thousands
Total Children 	total children in the family
Children Under 25	total children in the family under the age of 25
Education	 BA/BS or Masters
Occupation 	Professional, Manager, or Physician
Homeowner	whether or not they own a home
Vacation Home Owned	whether or not they own a vacation home
Total Cars Owned	number of total cars
Commute Distance	commute distance to the golf club
Age	age in years
Total Purchases in October	Purchases in October since it is a peak in sales purchases
Tee Time Purchases 	Total amount in dollars of tee time purchased from 2012-2014
Dinner Purchases 	Total amount in dollars of dinners purchased from 2012-2014

T-TEST RESULTS, PURPOSE AND APPLICATION
	The use of a T-test revealed the relationship between membership lifetime and marital status.  The impetus of this test began with a psychology study for marketing. “a process that applies marketing principles and techniques to create, communicate, and deliver value in order to influence target audience behaviors that benefit society as well as the target audience” (Cheng, Kotler, & Lee, 2009, p. 2). 
The relationship and research behind marketing a psychology has evolved to include such topics as neuromarketing and evolutionary psychology.  In the domain of marketing, evolutionary psychology has been used to examine marketing practices (Colarelli & Dettmann, 2003) to explain sex differences in motives for gift-giving (Saad & Gill, 2003), as a framework for neuromarketing (Garcia & Saad, 2008). The purpose of a study involving these factors is to develop a social responsibility to customers and businesses. In terms of marital status, which is the t-test that was performed here, there was significance around the membership length and marital status, however, not the case with gender. Research concludes, single individuals are more likely than married individuals (and those in a relationship) to engage in physical exercise for fun, to socialize, and to attract mates, as singles are more likely to focus on improving their attractiveness and appearance (Michaelidou & Moraes, 2014). This use of psychology and social awareness is put to place in the marketing application of the t-test results. The application will involve events and offerings that bring single individuals together. This purpose can also be directed towards those who may be less physically active and inspire them to become more so through a lifelong sport such as golf. 

 
The outcome of the T-test shows that those who are divorced, marital status coded as a 2 are typically having longer memberships in years. Another factor that came into important determination is age. For the divorced observations the average age was 54 and the married observations the average age was 53. Knowing that age was not a factor in the length of the membership, it can be concluded that there is a significant difference between these groups. The application involved for marketing strategies could target single individuals to visit the golf clubs to meet new people.

CHURN MODEL - BOOSTING, DECISION TREES, AND LOGISTIC REGRESSION
The data mining technique of boosting is a fairly new method that has grown rather popular in marketing research and data analysis.  Moreover, there is growing literature showing that bagging and boosting are applied in predicting churn based on personal social-demographic characteristics and past purchase behavior. More sophisticated versions of bagging, using weighted sampling schemes, exist under the name of boosting. (Lemmens & Croux 2006). This method of boosting works by applying weights to variables that are more impactful in predicting the outcome of the churn binary variable. With the awareness of this boosting, a logistic regression is run to cross check the variables that the boosting outcome produced. Boosting names certain variables as more important than others.  
	Within this dataset the boosting and logistic regression outcomes help determine which variables are most important. In the table below, the boosting is shown in a diagram called “importance.” This chart explains which variables are most important and weights can be applied to them. With this knowledge, the application can be focused on certain attributes for marketing automation, as well as, fine-tuning the model going forward.
	
 
	The plot shows that the tee time purchase is an important variable. This is seen again in out decision tree and logistic regression. Although the other variables weigh differently, it is valuable to know that tee time is important for all three. It is also true for the other tests that gender and vacation home were not important. This is an interesting outcome, where gender would typically make a difference, especially in sports since physical capacity is at play.
In the logistic regression output, the following table explains the group of individuals with a probability of 45% or greater to churn out of the 100-observation dataset. The logistic regression allows each individual observation to be identified and analyzed accordingly. 

 
Within the output, the variables can be examined more closely to trends and patterns. This is an important perspective of this data, but it is important to realize when the variables are statistically significant. Here, the commute distance of 16 miles matches the decision tree exactly. Other variables to focus on include Total children which we can see here are mostly more than 3, Vacation Home Owned, which is mostly not owned, age where most are over the age of 60, and number of cars which is either 2 or less. These are variables that can be analyzed with other tests as well and closely monitored. 
	There are certain variables to pay close attention to in the marked individuals who are most likely to churn. From these twelve observations, total purchases in October were 265 or less with many of them at zero. Tee time purchases are also low at 245 or fewer for a two year time period. For commute distance, the lowest is 16, while the number of cars owned is mostly 2 or less with the exception of two observations. With these insights, marketing department can decide where to direct their next strategy including how to create campaigns that are appealing to the specified customers and any customers that are similar to these observations more inclined to churn.
The ANOVA table for the logistic regression identifies the following variables as significant. 
Education level, which was coded as “0” for Bachelor’s and “1” for Master’s level, number of cars owned, total purchases in October, and total tee time purchases in the past two years. The following significant levels are shown below:

Predictor	Level of Significance	Coefficient
Education level	90% confidence           pr(>Chi) =0.08	 2.80
Number of Cars Owned	99% confidence 
pr(>Chi)=0.00 	-1.76
Total Purchases in Oct.	95% confidence 
pr(>Chi)=0.05	0.015
Tee time Purchases in past two years	95% confidence
pr(>Chi)=0.04	-0.015

These coefficients exhibit important characteristics of the customers. For tee time, is there is an increase in purchases this decreases the chance of churn, if there is an increase in cars, there is also a decrease in the chance of churn. The number of cars owned is very telling of the dataset. This shows that transportation to the golf club is a deterrent for customers and increases the chance of them leaving. Knowing which zip codes these customers are coming from will allow the clubs to plan for building alternate locations. This is a potential application of this data finding.
The decision tree output places three variables as most important, similar to the boost output of important variables. From the chart below, it is shown that the root is tee time purchase. If this is greater than $174 dollars, the chance of the customer churning is very low. If the tee time purchase sum is less than $174, the commute distance is greater than 16 miles, and the number of cars owned is less than 2, then the customer is likely to churn. Again commute distance becomes an important variable with the potential for several different applications in the churn analysis. The number of cars owned also is related to transportation and commute distance. Those members that have a lack of reliable transportation are more likely to leave their membership. 


 

The outcome of our models of boosting, logistic regression, and decision trees provides a conclusion for the dataset. The statistically significant variables include commute distance, number of cars owned, tee time purchase, education level, and total purchases in October. This means the dataset has several unique characteristics. In order to prevent churn, marketing initiatives applications can be building clubs in areas closer to those who are driving far, including a discount for those who travel far, increase discounts in October, and marketing more towards those with Bachelor’s degrees. 
The application will include targeted marketing offers based on previous purchases and customer churn prediction. Although clickstream (Hu & Zhong, 2008; Van den Poel & Buckinx, 2005) and other potential variables could be used, there are initial ways to understand the customer the company can benefit from and target according to the new variables of previously purchased items.  
These applications will lead to revenue increases and lower the risk for churn. The customers that are have a high probability of leaving their membership because of commute distance are actually in close proximity. Since this is the case, there could be the potential for an additional club to be built in that area. Another option is a shuttle or carpool for the members in that particular area. 
Location algorithms have been analyzed through several research initiatives. Location problems with preemptive strategies, anticipating the actions of future competitors, and dynamic location models, considering the opening of several facilities in different periods of time, could be analyzed. (Suárez-Vega, Santos-Peñate, & Dorta-González 2014). The ability to further research into what locations are optimal to expand into new locations is a possibility for the club to further its reach, influence, and revenues. This would also be important for golf clubs considering the land necessary to open successfully and the potential for competitors. Since location has become such an important variable, this may be the strategic next step for the club to investigate into where new locations could best be served and if certain locations now are being favored for features others do not offer.
REVENUE LOSS AND MARKETING BUDGET ALLOCATION BECAUSE OF CHURN
	In preventing the customer churn for the golf clubs, this will save the club any loss of related revenue. It is approximately $10,000 annually per 100 customers. That can be in upward revenue of $100,000 for clubs with 1,000 members or more. With a potential loss of revenue of this amount, placing marketing strategies in place would be increasingly important and save any potential loss in revenue with the right campaigns in place. The marketing budget can be allocated accordingly with placing importance on certain variables and formulating campaigns to target the audiences in risk of leaving.



CONCLUSION
	Churn is a powerful prediction tool for marketing in any company. In this study, a membership type business was used to show how churn could impact their customer profiles. In this study, the null hypothesis is rejected and it is seen that commute distance and tee time purchases have an effect on whether or not a customer will leave their membership. Many sports marketing could benefit from such an analysis. Marketing is a form of powerful communication that can connect people to communities when completed properly. The insight into psychology is valuable and should be used for improving social responsibility. The use of data insight dashboards can be implemented for understanding data as well as showing a predictive model. While all kinds of dashboards are valuable for the business, the purpose of this study was to understand the distinction between summarizing data and a predictive modeling dashboard. In creating a churn model the company is able to save potential revenue loss in an upward amount of $100,000 annually. The churn will also allow for a better allocation of marketing budget with more informed targeting decisions for campaigns. 











References
Cheng, H., Kotler, P., & Lee, N. R. (2009). Social marketing for public health: Global
trends and success stories. Sudbury, MA: Jones and Bartlett Publishers.

Colarelli, S. M., & Dettmann, J. R. (2003). Intuitive evolutionary perspectives in
marketing practices. Psychology & Marketing, 20, 837–865.

Dubin, R. (1969). Theory Building. The Free Press, New York.

Farquad, M.A.H., Ravi, V., Raju, S.B., Churn prediction using comprehensible support vector machine: An analytical CRM application

Garcia, J. R., & Saad, G. (2008). Evolutionary neuromarketing: Darwinizing the neu-
roimaging paradigm for consumer behavior. Journal of Consumer Behaviour, 7, 397–414.

Hu, J., & Zhong, N. (2008). Web farming with clickstream. International Journal of Information Technology & Decision Making, 7(2), 291–308. 

Hung, S. Y., Yen, D. C., & Wang, H. Y. (2006). Applying data mining to telecom churn management. Expert Systems with Applications, 31, 515–524.

Kim, Y.S., Lee, H., Johnson J.D. (2013) Churn management optimization with controllable marketing variables and associated management costs  Volume 40, Issue 6, May 2013, Pages 2198–2207 

Lemmens, A., & Croux, C. (2006). Bagging and boosting classification trees to predict
churn. Journal of Marketing Research, 43(2), 276–286.

Michaelidou, N., Moraes, C. (2014). “An Evolutionary Psychology Perspective on Physical Exercise Motives: Implications for Social Marketing.” Journal of Nonprofit & Public Sector Marketing, 26:162–183

Parzen, E. (2001). Comment on statistical modeling: The two cultures. Statistical Science. 16 224–226. MR1874152

Saad, G., & Gill, T. (2003). An evolutionary psychology perspective on gift giving
among young adults. Psychology & Marketing, 20, 765–784.

Shmueli, G. (2010). To Explain or To Predict? Statistical Science. Vol. 25, No. 3, 289–310

Suarez-Vega, R., Santos-Peñate, D.R., Dorta-González, P., (2014)Location and quality selection for new facilities on a network market. Ann Reg Sci 52:537–560

Van den Poel, D., & Buckinx, W. (2005). Predicting online-purchasing behaviour. European Journal of Operational Research, 166(2), 557-575.





