#  Titanic Dataset Analysis
  
In this project, I cleaned the data, handled missing values, converted text to numbers, normalized values, and removed outliers.

##  What I Did

- Checked the data types and missing values
- Filled missing values using median (for Age) and mode (for Embarked)
- Converted text columns like "Sex" and "Embarked" to numbers
- Normalized numeric columns using StandardScaler
- Visualized outliers using boxplots
- Removed outliers using the IQR method

## Dataset

I used the Titanic dataset. You can download it from:  
🔗 [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

## Tools Used

- Pandas – for handling data
- Seaborn and Matplotlib – for creating charts
- Scikit-learn – for encoding and normalization

## Output

- Clean data ready for machine learning
- Boxplots showing outliers before and after cleaning
- Improved data shape after removing noise
