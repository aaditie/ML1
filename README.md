# California House Price Prediction Model

 
This project aims to develop a predictive model for California house prices using machine learning techniques. I employed both Linear Regression and Random Forest Regressor algorithms to capture the relationships between various features and the target variable, median house value. The dataset used includes features such as longitude, latitude,total rooms, total bedrooms, population, households, median income, and the proximity to the ocean. I preprocessed the data by transforming skewed features and creating dummy variables for categorical data. To enhance model performance, I implemented hyperparameter tuning using GridSearchCV, optimizing parameters such as the number of estimators, maximum depth, and minimum samples for splitting and leaf nodes in the Random Forest model. I used Cross-validation  to ensure robust model evaluation and prevent overfitting. Then selected the  best-performing model  based on the evaluation metrics, the accuracy score was 0.817504796543049.
