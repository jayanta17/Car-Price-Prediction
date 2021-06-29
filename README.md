* **In this project, I tried to predict the price of a used car based on its past and present data.**
* After performing data preprocessing steps such as Removal of Outliers, Converting categorical data into numerical using _get_dummies_ and data visualizations, I found that **_Current Price_**, **_Fuel Type(being Diesel)_** and** _Transmission control_** are the most important features in deciding the price as shown in the fugure below.
  
![Features](Features.png)

* I built a model using RandomForestRegressor and a RandomizedSearchCV which gave a Mean Absoulte Error of only 60%.
