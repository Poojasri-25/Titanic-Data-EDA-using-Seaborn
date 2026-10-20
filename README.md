# Titanic-Data-EDA-using-Seaborn
 Perform an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover insights about the passengers and their survival rates. EDA helps in understanding the data's underlying patterns and relationships.

# Explanation:
The Titanic dataset is a classic example used for EDA. You'll clean the data, handle missing values, and visualize the relationships between different features and survival rates. The steps involved include:

# Data Cleaning: 
 Handle missing values for features like Age, Cabin, and Embarked.
 Feature Exploration: Analyze categorical features (e.g., Pclass, Sex, Embarked) and numerical features (e.g., Age, Fare).
# Visualization: 
 Use Seaborn and Matplotlib to create plots like bar charts, box plots, and heatmaps to visualize the relationships between features and survival rates.
# Insights: 
 Identify key factors that influenced survival rates, such as passenger class, gender, and age.

# Conclusion :  
 The columns that can be dropped are: 
  * PassengerId, Name, Ticket, Cabin: They are strings, cannot be categorized and don't contribute much to the outcome. 
  * Age,Fare: Instead, the respective range columns are retained.

The titanic data can be analyzed using many more graph techniques and also more column correlations, than, as described in this article.
Once the EDA is completed, the resultant dataset can be used for predictions.

