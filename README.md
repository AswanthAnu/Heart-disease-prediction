# Heart Disease Prediction
This project aims to predict whether a person has heart disease or not using machine learning techniques. The dataset used for this project is from Kaggle and contains various medical attributes such as age, sex, chest pain type, resting blood pressure, serum cholestrol, fasting blood sugar, resting ecg, max heart rate, exercise induced angina, oldpeak, slope, number of major vessels, thal.

## libraries
The following libraries were used in this project:
- Pandas for data manipulation and analysis
- Numpy for numerical computation
- Matplotlib and Seaborn for data visualization
- Scikit-learn (sklearn) for building and evaluating machine learning models

## Data Cleaning and Exploration
The dataset was cleaned to handle missing values and outliers. Exploratory data analysis (EDA) was also performed to gain insights into the data and understand the relationships between different features. Data visualization was used to better understand the distribution of the data and the relationship between different features.

## Feature Selection and Scaling
Features were scaled to ensure that all features were on the same scale and feature selection was performed to select the most relevant features for the model.

## Modeling
Three different machine learning algorithms were used: logistic regression, decision tree, and support vector classifier (SVC). Hyperparameter tuning was performed on the decision tree model using grid search and the best parameters were found to be criterion = entropy, max_depth = 5, and n_estimators = 15. The final model used was a random forest classifier with these parameters which resulted in an accuracy of 72%.

## Conclusion
This project was done for learning purposes and serves as a good example of the process of building a machine learning model from start to finish. The final model's accuracy is not as high as desired but the goal of this project was to learn the various steps involved in building a machine learning model, including data cleaning, EDA, feature selection, and modeling.

- Some boxplot and histogram
![image](https://user-images.githubusercontent.com/101197982/212450489-71ce9595-fba7-4f12-8adc-354bd4475da4.png)
- Correlation plot 
![image](https://user-images.githubusercontent.com/101197982/212450505-5b6f19a1-27d1-4155-870c-1ea162aa8665.png)
- Features used in Random Forest
![image](https://user-images.githubusercontent.com/101197982/212450567-160028f9-2304-41a3-a388-b6aa4240ee39.png)
- Random Forest 
![image](https://user-images.githubusercontent.com/101197982/212450587-d917fc70-010f-454a-abc7-b9996f1e5ff1.png)


