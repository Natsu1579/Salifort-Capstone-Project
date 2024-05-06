# Salifort Capstone Project

**Project Background** 

There is a high rate of turnover among Salifort employees. Salifort’s senior leadership team is concerned about how many employees are leaving the company. If Salifort could predict whether an employee will leave the company, and discover the reasons behind their departure, they could better understand the problem and develop a solution. Next, the leadership team asks you to analyze the survey data and come up with ideas for how to increase employee retention. 

**Business Problem**

To help with this, they suggest you design a model that predicts whether an employee will leave the company based on their job title, department, number of projects, average monthly hours, and any other relevant data points. A good model will help the company increase retention and job satisfaction for current employees, and save money and time training new employees. As a specialist in data analysis, the leadership team leaves it up to you to choose an approach for building the most effective model to predict employee departure. 

**Tools**

  1. Python
  2. Scipy
  3. scikit-learn
  4. Seaborn
  5. Matplotlib

**EDA Results** 

The data has been provided by the Google Advanced Data Analytics Professional Certificate Course. The dataset contains 14999 rows and 10 columns of features such as satisfaction levels, last evaluation, average monthly hours, etc. There was no missing data present, however, 3008 duplicates was found in the data so the decision was made to drop all of them. Next, the data was checked for outliers and handled accordingly. Finally, visualizations were made showing relationships between numerous variables in order to discover any correlations.  

**Conclusion** 

In order to solve the business problem, a Decision Tree and Random Forest model were made and compared to each other to see which model performed better. After conducting feature engineering, the decision tree model achieved an AUC of 96.9%, precision of 91.4%, recall of 91.6%, f1-score of 91.5%, and accuracy of 97.1%, on the test set. Despite that, the random forest model still modestly outperformed the decision tree model. 

<img width="477" alt="Screen Shot 2024-04-05 at 2 46 49 PM" src="https://github.com/Natsu1579/Salifort-Capstone-Project/assets/150382759/5e8627e9-7e54-4afd-a86d-d24b4fb0e865">

<img width="485" alt="Screen Shot 2024-04-05 at 2 47 17 PM" src="https://github.com/Natsu1579/Salifort-Capstone-Project/assets/150382759/98fd54cb-c4de-45f6-a09f-43dad2c97117">
