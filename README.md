# Tabular Data Processing with different models.
1) Perform Exploratory Data Analysis(EDA) and connect with BigQuery and utilize Data Studio.
2) Accelerate the model training.
3) Perform Different Models. 

## 1) EDA and Data Studio
- Upload the Dataset to the BigQuery with subscription given by professor.
- You can find my Exploratory Data Analysis [here](https://github.com/PLEX-GR00T/Machine_Learning/blob/main/BigQuery_with_EDA.ipynb).
- The visulization of the live dashboard with Data Studio is below.

![image](https://github.com/PLEX-GR00T/Machine_Learning/blob/main/outputs/DataStudio%20EDA.png)

## 2) Accelerate the model training.
- In this section to get use to all the models available I tried few basic models.
- Linear Regression, Lasso, Ridge, ElasticNet, Random Forest Regression.
- I have shown the training acceleration and accuracy comparison for the Linear Regression and Random Forest Regression.
- For this accelearation I have used Intel's OneAPI to acceleate the Data Mining Pipeline.
1) Linear Regression Training-Acceleration

<p float="left">
  <img src="https://github.com/PLEX-GR00T/Machine_Learning/blob/main/outputs/Linear%20Regression%20time.png" width="400" height="400" />
  <img src="https://github.com/PLEX-GR00T/Machine_Learning/blob/main/outputs/Linear%20Regression%20accuracy.png" width="400" height="400" /> 
</p>

2) Random Forest Regression Trainig-Acceleration

<p float="right">
  <img src="https://github.com/PLEX-GR00T/Machine_Learning/blob/main/outputs/Randome%20Forest%20time.png" width="400" height="400" />
  <img src="https://github.com/PLEX-GR00T/Machine_Learning/blob/main/outputs/Randome%20Forest%20Accuracy.png" width="400" height="400" /> 
</p>

- As we can see in linear regression, even after using the OneAPI for the acceleration, there is no difference in the accuracy.
- However, in the random forest regression we can see some significant decrease in the accuracy of the model after wards. 

## 3) Perform XGBoost, LightGBM, and Cat Boost.


| Models  | Score |
| ------------- | ------------- |
| XGBoost  | 0.974  |
| Cat Boost  | 0.795  |
| LightGBM  | 0.729  |
