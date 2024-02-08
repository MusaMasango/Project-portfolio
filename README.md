# Project Portfolio
data science project portfolio
# [Project 1 : BigData on the spread of COVID-19 in the world : Project overview](https://github.com/MusaMasango/BigData-on-the-spread-of-COVID-19-in-the-world)
* Downloaded data from open sources,
* Performed preliminary data cleaning
* Performe correlation and EDA analysis.
* Built models using 2 different frameworks (linear regression and time series).
* Built a forecast and analyzed the accuracy and adequacy of the obtained models.
* Visualized the dynamics of COVID-19 infection spread on interactive maps

![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/pivot%20table.png)
![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/covid%20cases.png)

# [Project 2 : loan-prediction-machine-learning-project : Project overview](https://github.com/MusaMasango/loan-prediction-machine-learning-project)

In finance, a loan is the lending of money by one or more individuals, organizations, or other entities to other individuals, organizations etc. The recipient (i.e., the borrower) incurs a debt and is usually liable to pay interest on that debt until it is repaid as well as to repay the principal amount borrowed. (wikipedia). The major aim of this project is to predict which of the customers will have their loan approved. This is important especially for the banks as they have to be sure that a particular customer meets the requirements for loan approval. 
 
I was able to model the loan_status of the customers with a 78% accuracy after minimal tuning. This result however can be further improved with better data as well as other useful information.

![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/bar%20graph.png)
![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/correlation%20plot.png)
![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/credit%20history.png)
![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/loan%20amount.png)
![](https://github.com/MusaMasango/Project-portfolio/blob/main/images/applicant%20income.png)

# [Prjoect 3: Sales Insights Analysis Project : Project overview](https://github.com/MusaMasango/Sales-Insights-Project)
* Downloaded data from open sources.
* Performed preliminary data analysis using MySQL.
* Performed extract, transform and load using Tableau.
* Plotted different types of graphs to showing the relationship between revenue, profit, sales and markets.
* Built 2 different automated dashboards on Tableau (Revenue analysis and Profit analysis).
* Determined the Top 5 customers and products based on revenue.

![profit trend](https://github.com/MusaMasango/Sales-Insights-Project/blob/main/Profit%20trend.jpg)
![revenue by year](https://github.com/MusaMasango/Sales-Insights-Project/blob/main/Revenue%20by%20year.jpg)

# [Project 4 : credit-card-fraud-detection-project : Project overview](https://github.com/MusaMasango/Credit-Card-Fraud-Detection-Project)

In this machine learning project, we solve the problem of detecting credit card fraud transactions using machine numpy, scikit learn, and few other python libraries. We overcome the problem by creating a binary classifier and experimenting with various machine learning techniques to see which fits better.
 
Through this project, I applied techniques to address the class imbalance issues and achieved an accuracy of more than 90%. The random forest model yields a very good performance as indicated by the model accuracy which was found to be 0.99990035.
To address the issue of class imbalance problem, we used the oversampling technique, this was done by the SMOTE package imported from the imblearn module.

ROC AUC of our models approaches towards 1. So, we can conclude that our classifier does a very good job in predicting whether a transcation is genuine or fraud.

![bar graph](https://github.com/MusaMasango/Credit-Card-Fraud-Detection-Project/blob/main/labels%20bar%20graph.png)
![correlation matrix](https://github.com/MusaMasango/Credit-Card-Fraud-Detection-Project/blob/main/correlation%20matrix.png)
![model accuracy comparison](https://github.com/MusaMasango/Credit-Card-Fraud-Detection-Project/blob/main/model%20accuracy%20comparison%20table.png)

# [Project 5 : Customer-Segmentation-Project : Project overview](https://github.com/MusaMasango/Customer-Segmentation-Project)

In this python machine learning project, I built a clustering model using the kmeans algorithm applied on a mall customer dataset. This project aims to determine the types of customers (target customers) who can easily convert into loyal customers so that the marketing team can make an informed decision about their approach.

The correlation matrix shows that there is a strong positive correlation between the CustomerID and the Annual Income given by a correlation coefficient of 0.98. In addition, there is a strong negative correlation between the Age and the Spending Score given by -0.33. This shows that older customers spend less compared to the younger customers. This makes sense intuitively since older customers earn less than the younger customers (correlation coefficient = -0.01), hence older customers are less likely to spend since they earn a small income compared to the younger customers who earn more.

For clustering problems, we often choose the result that has the highest silhouette score, since it measures the seperation between the clusters. In general, the higher the score, the far apart the clusters are, which is often good since we do not want to have an overlapping within the clusters that might lead to incorrect grouping of data. In our case, we can see from the silhouette score table that the best relationship is between the Age and Spending Score (1-100) having an Silhouette score of 0.499739 when compared to the other relationships. Therefore, the marketing team of the mall should focus on this group when conducting customer segmentation.

![image 5](https://github.com/MusaMasango/Project-portfolio/blob/main/images/image%205.png)
![image 9](https://github.com/MusaMasango/Project-portfolio/blob/main/images/image%209.png)
![image 10](https://github.com/MusaMasango/Project-portfolio/blob/main/images/image%2010.png)
![image 15](https://github.com/MusaMasango/Project-portfolio/blob/main/images/image%2015.png)
