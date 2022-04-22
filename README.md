# SC1015 Data Science Mini-Project

Our team's objective is to utilise the data sets of Video games from year 1980 - year 2017 to predict the Global Sales of a certain game in that period. Our Video Games data sets consists of Game related information such as Rank, Name, Platform, Year, Genre,Publisher, NA Sales, EU Sales, JP Sales, Other Sales and Global Sales.  

We will be focusing our models on projecting global sales in particular. As a result, columns like NA Sales, EU Sales, JP Sales, and Other Sales will be dropped. We will start by extracting data and visualizing it. Then, using Global Sales, we look at the boxplot and remove any outliers from our data. After our video games data set has been cleaned, we will move on to exploratory data analysis. Lastly, we will be focusing on the three commonly used Machine Learning Algorithms in Python which are Linear Regression, Random Forest and Gradient Boosting Regression. We will analyze our models based on the predicted and actual value of Global Sales.

### Jupyter Notebook #1: Data Extraction, Cleaning and Exploratory Data Analysis (EDA)

  Remarks: In this section, we will be focusing on the extraction and data cleaning of our Video Games dataset. In our data cleaning, we cleaned out those data that              has na values. Next, we extract the outliers of our data based on Global Sales and dropped them as well. We will also be focusing on the data visualization and exploratory analysis of our Video Games dataset. We can see some interesting trends from            our datasets regarding their Genre, Publisher, Platform and Year.  
  
### Jupyter Notebook #2: Machine Learning - Regression (Linear, GradientBoosting, Random Forest)
  Remarks: In this section, we will be focusing on utilising Linear Regression, GradientBoosting Regression and Random Forest model for our Video Games dataset. We split   our data according to their train and test sets and constructed 3 different models based on our train datasets. We analyzed the model and calculated their explained variance(R squared) for both train and test sets. We compare their goodness of fit and choose the best model for our prediction. We will use the better model to predict Global Sales of our Video Game.  
 

###### VGsalesSlides.pptx
Remarks: Our slides for our presentation.






###### Individual Contribution:

Dexter Voon - train and test split, Machine learning models and prediction 


Derrick Ng - Data Extraction, data cleaning, data visualization and EDA



###### References: 

https://www.displayr.com/what-is-a-random-forest/#:~:text=Disadvantages%20of%20random%20forests&text=A%20forest%20is%20less%20interpretable,from%20several%20hundred%20individual%20trees.

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html

https://blog.paperspace.com/gradient-boosting-for-classification/

https://towardsdatascience.com/considerations-when-choosing-a-machine-learning-model-aa31f52c27f3

https://www.kaggle.com/datasets/arslanali4343/sales-of-video-games
