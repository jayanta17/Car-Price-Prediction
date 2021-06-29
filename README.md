* **In this project, I tried to predict the price of a used car based on its past and present data.**
* **After performing data preprocessing steps such as Removal of Outliers, Converting categorical data into numerical using _get_dummies_ and data visualizations, I found that **_Current Price_**, **_Fuel Type(being Diesel)_** and **_Transmission control_** are the most important features in deciding the price as shown in the figure below.**
<br>
  
![Features](Features.png)

* **The model was built using **_RandomForestRegressor_** and the hyperparameter tuing was done using _**RandomizedSearchCV.**_**
* **After performing these steps,model gave an RMSE of about 96%.**
