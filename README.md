# Sprocket
![Sprocket Header](https://github.com/xavier-lim/sprocket/blob/master/images/header.jfif)

As part of KPMG's Data Analytics Consulting Virtual Internship, I created this project to help Sprocket Central Pty Ltd, a fictional Australian company that sells bikes, determine which new customers to target. I created multiple machine learning algorithms (decision tree, random forest, and gradient boosting) to predict the amount of profit a new customer will generate, based on customer demographics and attributes. The company can use my model to maximize future profits.


## Table of Contents
1.	[Project Tools](https://github.com/xavier-lim/sprocket#project-tools)
2.	[Data Source](https://github.com/xavier-lim/sprocket#data-source)
3.	[Tableau Project Dashboards](https://github.com/xavier-lim/sprocket#tableau-project-dashboards)
4.	[Model Predictor Variables](https://github.com/xavier-lim/sprocket#model-predictor-variables)
5.	[Conclusion](https://github.com/xavier-lim/sprocket#conclusion)
6.	[Acknowledgements](https://github.com/xavier-lim/sprocket#acknowledgements)
7.	[Author](https://github.com/xavier-lim/sprocket#author)

## Project Tools
*	Python
*	Jupyter Notebook
*	Tableau - [Download Tableau](https://www.tableau.com/products) 
*	Transactions Data Frame Source – “Transactions” Sheet of KPI_VI_raw_data.xlsx
*	New Customer List Data Frame Source – “NewCustomerList” Sheet of KPI_VI_raw_data.xlsx
*	Customer Demographic Data Frame Source – “CustomerDemographic” Sheet of KPI_VI_raw_data.xlsx
*	Customer Address Data Frame Source – “CustomerAddress” Sheet of KPI_VI_raw_data.xlsx

## Data Source
All the data for this project was collected from [InsideSherpa](https://www.insidesherpa.com/virtual-internships/m7W4GMqeT3bh9Nb2c):

1.	The **Transactions** data set presents information about *20,000* transactions such as the transaction ID, product ID, product line, product class, list price, and cost.
2.	The **New Customer List** data set presents information about *1000* new customers such as their name, gender, date of birth, job industry, wealth segment, and location.
3.	The **Customer Demographic** data set presents information about *4000* current/past customers such as their customer ID, name, gender, date of birth, job industry, and wealth segment.
4.	The **Customer Address** data set presents location information about *4000* current/past customers.


## Tableau Project Dashboard
![Demographics](https://github.com/xavier-lim/sprocket/blob/master/images/customer_demographics.PNG)

Interactive Version: [Sprocket Dashboards](https://xavier-lim.github.io/SprocketDashboards.html)


## Model Predictor Variables
![Categorical Variables](https://github.com/xavier-lim/sprocket/blob/master/images/categorical_variables.PNG)

---

![Numerical Variables](https://github.com/xavier-lim/sprocket/blob/master/images/numerical_variables.PNG)

---

![Feature Importance](https://github.com/xavier-lim/sprocket/blob/master/images/feature_importance.PNG)


## Conclusion
Most of the company's profits come from women in their 40s, who are mass customers in the New South Wales (Australia) area, working in the financial services, manufacturing, or health industry. However, according to my prediction model, the company should focus marketing towards men in their early 20s or 65+, who have made many bike related purchases in the past, and have been working in the retail, entertainment, financial services, and health industry for many years (long tenure). Although there are not as many current customers in this demographic group, they generate the highest average profit.



## Acknowledgements
  * [KPMG Virtual Experience Program with InsideSherpa](https://www.insidesherpa.com/virtual-internships/m7W4GMqeT3bh9Nb2c)

## Author

* **Xavier Lim** - [LinkedIn](https://www.linkedin.com/in/xavier-lim14/)  |  [Portfolio Website]( https://xavier-lim.github.io/)  |  [Tableau Public](https://public.tableau.com/profile/xavier.lim#!/)
