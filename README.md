# Employer Leave Prediction

# *Overview*

The goal of this project was to create a multiple linear regression and random forest model to predict wether or not an employee will leave the compagny. This project utilized insights provide to the Human Resources Department in Salifort Motors for ten years. The final random forest model achieved AUC of 93.84%, precision of 87%, accuracy of 96%, f1_score of 88 % and recall of 90.36% determining what features were most important to determine employees left. 
Based on the model, last evaluation, number of project, tenure and overworking were most influential in they leaving.

# *Business Undestanding*

The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. They have the following question: what’s likely to make the employee leave the company? It's important to understand what factors encourage employees to leave the compagny.

# *Data Understanding*

The data come from to the Human Resources Department of [Salifort Motors](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). The data consisted approximately 15k unique trips and 10 features. The features included information satisfaction level, number of project, promotion for last 5 years and left. The bar chart below shows how many employees left the company versus stayed that exist in the data set.

![image-3.png](attachment:image-3.png)

Multiple redundant columns were dropped and reformatted into the proper data type.

# *Modeling and Evaluation*

A random forest model comprising 100 decision trees was used to determine feature importance in who would employee leave or not. The below plot shows that last evaluation, number of project and tenure were the Top 3 most important factors in determining in they leaving. The overall model performed with 96% accuracy and 87% precision.

![image-2.png](attachment:image-2.png)

# *Conclusion*

The models and the feature importances extracted from the models confirm that employees at the company are overworked. 

To retain employees, the following recommendations could be condider

* Cap the number of projects that employees can work on.
* Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied. 
* Either reward employees for working longer hours, or don't require them to do so. 
* If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear. 
* Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts. 
* High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort. 
