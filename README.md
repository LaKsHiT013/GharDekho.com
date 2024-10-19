# GharDekho.com

GharDekho.com is a comprehensive Data Science project focused on real estate analytics. The project consists of three main modules:<br>

- **Price Predictor**: Predict property prices based on various features.<br>
- **Recommendation System**: Recommends properties based on user preferences and historical data.<br>
- **Price Analyzer**: Analyzes trends in property prices using advanced data visualization techniques.<br>

## Project Structure
This project includes 13 Jupyter notebooks that cover the entire Data Science pipeline, from data preprocessing to building and evaluating machine learning models.

## Notebooks Overview:

### Feature Engineering:
Focused on generating new features from the raw dataset to improve model performance. Key features include price per square foot, location proximity to amenities, and property age. These engineered features were crucial in enhancing predictive power for both price prediction and the recommendation system.

### Exploratory Data Analysis (EDA):
Conducted detailed analysis across three levels:<br>
- **Univariate**: Examined distributions of individual variables like price, area, and room count to detect outliers and skewness.<br>
- **Bivariate**: Analyzed relationships between key features, including how location and property size correlate with price using scatter plots and correlation analysis.<br>
- **Multivariate**: Visualized interactions among multiple variables, identifying trends such as the effect of location, property type, and amenities on price through pair plots and heatmaps.

### Feature Selection:
Implemented correlation analysis and machine learning techniques to identify the most influential features for model building. Applied methods like correlation matrices to remove multicollinearity and employed feature importance metrics from models like Random Forest to choose the best predictors for price prediction and recommendations.

### Data Preprocessing:
Cleaned and prepared the dataset by handling missing values using imputation methods, detecting and treating outliers, and scaling numerical data through standardization. This ensured the data was ready for machine learning models and avoided issues like skewed results or poor performance due to inconsistent scales.

### Data Visualization:
Created comprehensive visualizations to uncover trends and patterns in the data. For univariate analysis, used histograms and box plots to showcase the spread of key features. For multivariate analysis, employed scatter plots and heatmaps to display interactions between features, which helped in better understanding property price drivers and relationships.

### Model Building:
Developed and evaluated machine learning models for two primary goals:<br>
- **Price Predictor**: Built regression models including Linear Regression, Decision Trees, and XGBoost, with extensive hyperparameter tuning to predict property prices.<br>
- **Recommendation System**: Created a hybrid recommendation system combining collaborative filtering and content-based filtering, providing personalized property suggestions to users based on preferences and historical data.

## Modules

### 1. Price Predictor
A machine learning model that predicts property prices based on key features such as location, size, and amenities. Various regression models are employed, including:<br>
- Linear Regression<br>
- Decision Trees<br>
- XGBoost

### 2. Recommendation System
A personalized recommendation system to suggest properties to users based on their preferences. It uses collaborative filtering and content-based filtering techniques.

### 3. Price Analyzer
An analytical tool that provides insights into historical trends and future predictions of property prices. The price analyzer helps users make informed investment decisions.

## Conclusion
GharDekho.com leverages the power of Data Science and Machine Learning to provide actionable insights for both property buyers and investors. The combination of price prediction, personalized recommendations, and in-depth price analysis makes this project a valuable tool for real estate decision-making.
