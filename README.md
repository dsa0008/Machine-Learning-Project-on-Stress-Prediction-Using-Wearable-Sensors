# Machine-Learning-Project-on-Stress-Prediction-Using-Wearable-Sensors

# Dataset Analysis and Machine Learning Model Summary

## About this Dataset

This dataset consists of approximately 11.5 million entries across nine columns, capturing various physiological and orientation data points. It is designed for stress detection, health monitoring, or broader research applications.

### Dataset Columns Description

- **X, Y, Z**: Orientation data with 256 unique values each.
- **EDA (Electrodermal Activity)**: Measures skin conductance with 274,452 unique values.
- **HR (Heart Rate)**: Heart rate measurements with 6,268 unique values.
- **TEMP (Temperature)**: Temperature readings with 599 unique values.
- **id**: Identifier for subjects or entities with 18 unique values.
- **datetime**: Timestamps with about 10.6 million unique values.
- **label**: Categorical classification with three unique values.

### Data Analysis Techniques

Utilized Python libraries such as Pandas for data manipulation, and Matplotlib and Seaborn for visualization. Techniques include:

- Data cleaning and exploratory data analysis (EDA).
- Visualization of data distributions and correlations.
- Grouping data to analyze maximum values and trends.

### Machine Learning Models

Six machine learning models were trained to predict stress levels from physiological variables:

1. **Random Forest Classifier**: Achieved a high accuracy of 99.64%.
2. **Logistic Regression**: Showed underperformance with a negative R-squared score.
3. **K-Nearest Neighbors (KNN)**: Outperformed the Logistic Regression model.
4. **Neural Networks**: Reached an accuracy of 0.84 on the test set.

EDA was identified as the most significant predictor of stress.

### Recommendations

- Address class imbalance within the dataset.
- Evaluate the importance of physiological signals for accurate stress detection.
- Optimize for recall to improve prediction accuracy.
- Ensure the algorithm's decision-making process is transparent and interpretable.

### Conclusion

This project demonstrates the application of machine learning models to predict stress levels from physiological data, emphasizing the importance of data preprocessing, model selection, and the integration of domain knowledge for enhanced model performance.

