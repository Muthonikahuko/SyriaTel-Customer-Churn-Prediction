# SyriaTel-Customer-Churn-Prediction
![Purple phone](https://github.com/Muthonikahuko/SyriaTel-Customer-Churn-Prediction/assets/54804370/0f2fde00-611e-4405-97a6-597080f7796b)

### Author : Muthoni Kahuko

---

### Business Understanding
SyriaTel, a telecommunications company, is facing a high churn rate as many customers are stopping to do business with them. The company wants to address this issue and figure out how to reduce money lost because of customers who don't stick around very long.

The company has requested that data analysts develop a model that can predict customer churning. SyriaTel aims to gain insights into factors associated with churn in order to reduce the rate, increase customer retention, and overall grow profit.

*Churn - the rate at which customers stop doing business with a company over a given period of time.*

---

### Data Understanding
In this project, we used a dataset from Kaggle. The dataset contains information on Syriatel customers: Usage patterns, plans as well and churn. The dataset contains 3333 records and 21 columns.

---

### Data Preparation
After a quick overview, we realized the data has no missing values and due to privacy, we dropped the 'Phone number' column.

---

### Exploratory Data Analysis (EDA)
Churn Distribution
Out of the 3333 customers in the dataset, we can see that about 500 people have stopped doing business with SyriaTel while 2850 customers have remained with SyriaTel therefore we have a 14.5% Churn rate
![newplot](https://github.com/Muthonikahuko/SyriaTel-Customer-Churn-Prediction/assets/54804370/309d7c60-c87f-4f99-8bd3-d499d5678398)

Distribution of Area Code Feature
We realize that almost half of the customers are in area code 415
![newplot (1)](https://github.com/Muthonikahuko/SyriaTel-Customer-Churn-Prediction/assets/54804370/f48f4627-69e2-4560-ae48-def681e64475)

Distribution of features
From the graphs above we can see that a lot of the columns have a normal distribution apart from customer service calls and a number of vmail messages.
![download (2)](https://github.com/Muthonikahuko/SyriaTel-Customer-Churn-Prediction/assets/54804370/3a83bcda-21ba-4b7c-ad91-2fad6bc9cd4f)

---

### Modeling and Model Evaluation
I split the data (80/20) 80% was the train set while 20% was the test set.
Using 3 algorithms:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

It was noted that the Random Forest Classifier was the best algorithm with a recall rate of 0.79

![Recall rate](https://github.com/Muthonikahuko/SyriaTel-Customer-Churn-Prediction/assets/54804370/bc6aa43c-5405-481f-b7d8-6097ba7611aa)

---

### Conclusion and Recommendations
- Offer discounts and offers to customers in area codes 415 and 510 as these areas have a high churn rate. This can reduce the rate at which customers leave the company

- Evaluate the pricing structure for day, evening, and international charges. Consider adjusting pricing plans, introducing special offers and discounts to address the customers who leave due to higher chargers

- Focus on customer retention strategies for states with higher churn rates like Texas, New York, and New Jersey. This can involve targeted marketing, discounted rates, and better customer support in those states
  
- Improve customer service quality and reduce the number of customer service calls. Enhance training programs for customer service representatives to ensure prompt and effective resolution of customer issues, leading to higher customer satisfaction and reduced churn.





