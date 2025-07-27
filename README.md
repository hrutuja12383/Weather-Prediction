# Weather-Prediction-

PROBLEM STATMENT:- Using machine learning concepts, need to predict the weather condition.The weather condition may be drizzle,rain,sun,snow,fog. This weather condition are decided by year and month.

Description:- The Weather Dataset is a information about the weather condition of Month. It records precipitation, maximum temperature, miniimum temperature, Wind speed. This Dataset available as a csv file. We are going to analyze this dataset using Panda's data frame.

### About Dataset:- 

Using the Columns :
````
precipitation

tempmax

tempmin

wind
````


### OBJECTIVE:- 

We are going to predict the weather condition :
````
drizzle

rain

sun

snow

fog
````


1.Importing the Essential Libraries

2.Loading the Data using CSV file

3.Checking for missing or nan values

4.Get the count of missing values in each column of a dataframe.



### DATA VISUALISATION:-

For data visualisation we use MATPLOTLIB & SEABORN libraries.

1. MATPLOTLIB:-

- Matplotlib is an amazing visualization library in Python for 2D plots of arrays.
- Matplotlib consists of several plots like line, bar, scatter, histogram etc.

2. SEABORN:-

- Seaborn is an amazing visualization library for statistical graphics plotting in Python.
- It provides beautiful default styles and color palettes to make statistical plots more attractive.

5.Finding values of outliers(IQR method)

- Checking for the presence of outliers in numeric cols
  Outlier is an observation that appears far away and diverges from an overall pattern in a sample.

- Outliers in input data can skew and mislead the training process of machine learning algorithms resulting in longer training times, less accurate models and          ultimately poorer results.



6.Dealing this problem with Seven machine learning models.(Classification)
````
   a.LogisticRegression

   b.KNeighbors
   
   c.SVC(Support Vector Classification)
   
   d.Gaussian Naive Bayes (GaussianNB)
   
   e.RandomForest
   
   f.SGD(stochastic gradient descent)
   
   g.Gradient Boosting

````
7.We have predicted the Weather using Seven different ML model algorithms. 

The percentage of:-

1. LogisticRegression= 78.42%

2. KNeighbors= 73.22%

3. SVC(Support Vector Classification)= 78.14%

4. Gaussian Naive Bayes (GaussianNB)= 83.16%

5. RandomForest= 78.42%

6. SGD(stochastic gradient descent)= 68.85%

7. Gradient Boosting= 82.24%



### Conclusion:-
    
    - Out of seven machine learning algorithms we applied, 
    - We conclude that Gaussian NB classifier performs the best on this dataset with 83.61% Accuracy


## Dashboard
Dashboard is designed from Microsoft Power BI
- ![Screenshot (523)](https://user-images.githubusercontent.com/108801533/189523191-f5c3acf4-c702-47ef-8b23-b7a237755354.png)
- ![Screenshot (525)](https://user-images.githubusercontent.com/108801533/189523188-17f093de-29b3-4643-9c94-43f578742a9b.png)
