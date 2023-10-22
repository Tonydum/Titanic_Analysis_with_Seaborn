# Titanic Dataset Analysis

Overview

This project entails a thorough analysis of the Titanic dataset, which comprises various details about the passengers on board the ill-fated maiden voyage of the RMS Titanic. The analysis covers data loading, exploration, cleaning, visualization, statistical analysis, data manipulation, and machine learning to predict passenger survival.

1. Data Loading and Exploration
1.1 Libraries Import
The following libraries were imported for data manipulation, visualization, and analysis:

Pandas
NumPy
Seaborn
Matplotlib
1.2 Dataset Loading
The Titanic dataset was loaded from a local CSV file, which includes information such as passenger class, age, fare, survival status, and other relevant details.

1.3 First Look at the Data
The first five rows of the dataset were displayed to ensure proper loading and to get an initial understanding of the data structure.

1.4 Data Summary
A summary of the dataset was provided, detailing the data types, non-null values, and memory usage.

2. Data Cleaning
   
2.1 Missing Values
Missing values were identified in the "age", "embarked", "deck", and "embark_town" columns. Strategies were employed to address these:

Missing "age" values were filled with the median age.
Rows with missing "embarked" values were dropped.
The "deck" column was left as-is due to a large number of missing values.

3. Data Visualization
   
3.1 Passenger Class Distribution
A count plot was used to visualize the distribution of passengers across different classes, showing a majority in the Third class.

3.2 Age Distribution
A histogram displayed the age distribution of passengers, highlighting a concentration in the 20-30 years range.

3.3 Age Distribution by Class
A box plot compared the age distribution across different passenger classes.

4. Statistical Analysis
   
4.1 Average Age
The average age of passengers was calculated to be approximately 29.32 years.

4.2 Survival Rate
The overall survival rate was found to be approximately 38.25%.

4.3 Survival Rate by Class
Survival rates were compared between different passenger classes, showing higher survival rates in higher classes.

4.4 Survival Rate by Gender
A significant difference in survival rates between male and female passengers was observed.

5. Data Manipulation
   
5.1 Age Group Categorization
A new "age_group" column was created to categorize passengers as "Child", "Adult", or "Senior".

5.2 Average Fare by Class
The average fare paid by passengers in each class was calculated.

5.3 Common Embarkation Points
The top 5 most common embarkation points were identified.

6. Advanced Visualization
   
6.1 Correlation Heatmap
A heatmap visualized the correlation between numerical features.

6.2 Age Distribution by Class (Violin Plot)
A violin plot was used to visualize the distribution of passenger ages for each class.

6.3 Pair Plot
A pair plot provided a comprehensive view of relationships and distributions between "age", "fare", "pclass", and "survived".

7. Machine Learning
   
7.1 Logistic Regression Model
A Logistic Regression model was employed to predict passenger survival, achieving an accuracy of 82.40%.

7.2 Model Evaluation
The model’s performance was evaluated using accuracy, precision, recall, and F1-score.

7.3 Predicted Survival Rate
The predicted survival rate based on the model's predictions was approximately 31.84%.

Conclusion

This comprehensive analysis provided valuable insights into the Titanic dataset, showcasing the power of data manipulation, visualization, and machine learning in understanding historical events and deriving meaningful patterns. The project is a testament to the significance of data science in various domains.

