The understanding of the appliances energy use in buildings has been 
the subject of numerous research studies, since appliances represent a significant 
portion (between 20 and 30% ) of the electrical energy demand.
The dataset contains features such as: Temperature and Relative Humidity of 
different regions of the House, indoor and outdoor temperatures, weather features 
such as Windspeed, visibility, Pressure, our target variable appliance and Time stamp 
of every 10 mins.

The approach we followed:
- Data Understanding
- EDA
- Data Preprocessing
- Building Models
- Choosing the best Model based on the appropriate evaluation metric for our problem statement

The data we were given mostly contained weather Data The data provided was 
structured and in a tabular format. Our first step was to understand each of the 
features, exploring the permissible values each of these features can take, and 
understanding its relation with the Target variable.
We performed univariate and bivariate analysis on the data to understand their 
distributions and relationship with the target variable. We saw that the data has 
Outliers. We also performed multivariate analysis to check for correlations between 
the features, and the target variable.

Our next step was to preprocess the data. Here we didn’t have missing value. We 
applied transformation to reduce skewness in the data. We used Date column to 
extract week and hours from it and see the appliance energy accordingly.
We Measured our results on Root mean squared error and R2 Score.
We built various models like Linear Regression, Support Vector Machine, Random 
Forest and XGBoost. And we also did the Other Ensemble techniques of Voting 
Regressor, Average Regressor and Stacking Regressor.
We performed cross validation and hyper parameter tuning and each of these 
models. Stacking Regressor gave us the best R2 score. With , Ensemble techniques 
and Cross validation we were able to increase our r2 score even more. 
