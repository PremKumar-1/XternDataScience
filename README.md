# VeloCityX Fan Engagement Analysis

This project analyzes fan engagement data from VeloCityX with the goal of predicting virtual merchandise purchases based on fan interaction metrics such as challenges completed, time spent on Live 360, and sponsorship interactions. This analysis will help VeloCityX better understand user engagement and optimize future challenges for more interaction.

## Tasks Covered:
- **Data Gathering**: Compiled user engagement metrics like Fan Challenges Completed, Predictive Accuracy, and Time on Live 360.
- **Data Cleaning and Processing**: Cleaned and prepared the dataset for analysis by addressing missing values and normalizing the data where necessary.
- **Exploratory Data Analysis (EDA)**: Used visualizations like heatmaps and scatter plots to uncover correlations between fan engagement metrics and merchandise purchases.
- **Modeling**: Applied machine learning models such as Random Forest, Logistic Regression, Gradient Boosting, and SVM to predict merchandise purchases.
- **Evaluation**: Evaluated models using accuracy scores and cross-validation to assess their generalization performance.
- **Feature Engineering**: Created interaction features such as **Fan Challenges Completed** × **Time on Live 360** to improve model performance.

## Methods Used:
- **Pandas**: For data cleaning and analysis.
- **Seaborn & Matplotlib**: To visualize data relationships and model results.
- **Scikit-Learn**: For building and evaluating machine learning models.
- **SMOTE**: Addressed data imbalance by generating synthetic samples.
- **Random Forest & GridSearchCV**: Tuned the Random Forest model using hyperparameter search.
- **Cross-Validation**: Used cross-validation to validate model performance.

## Results:
- **Model Performance**: The **Random Forest model** showed the best performance with an accuracy of 39.29% and an average cross-validation score of 38.57%. While the accuracy is moderate, it offers insights into fan engagement behavior.
- **Insights**: The analysis found a positive correlation between **Fan Challenges Completed** and **Time on Live 360** with **Virtual Merchandise Purchases**, indicating that higher engagement leads to more purchases.
- **Visualization**: The results are displayed using heatmaps, scatter plots, and feature importance charts to help understand the relationship between different engagement metrics and purchases.

## Visualizations:
- **Correlation Heatmap**: Demonstrates relationships between fan engagement metrics and merchandise purchases.
- **Scatter Plots**: Visualizes how fan challenges and Live 360 time affect sponsorship interactions and merchandise purchases.
- **Feature Importance Plot**: Shows the most significant features for predicting merchandise purchases.

## Proposed Fan Challenge:
I recommend a new **Fan Challenge** where users predict **which team will have the highest number of sponsorship interactions**. Based on the analysis, sponsorship clicks and time spent on Live 360 strongly influence merchandise purchases, making this a great way to drive engagement.

## Tags:
- Fan Engagement
- Merchandise Prediction
- Machine Learning
- VeloCityX
- Random Forest
- SMOTE
- Cross-Validation
- Data Visualization
- Feature Engineering
