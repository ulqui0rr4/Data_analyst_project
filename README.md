# Project Summary

**1. Iris Classification - Machine Learning Project**

Overview
This project builds a classification model to predict Iris species (Setosa, Versicolor, Virginica) based on sepal and petal measurements. It serves as an introductory machine learning problem and explores data preprocessing, visualization, model training, and evaluation techniques.

Technologies Used
- Programming: Python (Jupyter Notebook, VS Code)
- Data Handling: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning Models: KNN, Decision Trees, Random Forest, SVM, Logistic Regression
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
  
Project Steps
- Data Exploration: Understanding dataset features and distributions
- Preprocessing: Handling missing values, feature scaling, data splitting
- Model Training: Comparing different classification algorithms
- Hyperparameter Tuning: Optimizing model performance with Grid Search
- Evaluation: Assessing accuracy and visualizing results
- Insights: Feature importance analysis and decision boundary visualization
  

**2. Olympics Data Analysis**

A comprehensive data exploration and machine learning project analyzing Summer Olympics medal statistics from 1976 to 2008. Built using Python, SQL, and Excel, this beginner-friendly project demonstrates key data analytics techniques while offering insights into Olympic history.

Project Overview
This project investigates patterns in Olympic medal distribution, athlete performance, gender-based participation, and country dominance. It combines Exploratory Data Analysis (EDA) with basic predictive modeling to determine medal outcomes based on athlete attributes.

Tools and Technologies
| Tool | Purpose | 
| Python | Data processing, visualization, and ML modeling | 
| Pandas | Data manipulation and cleaning | 
| Matplotlib / Seaborn | Visualizations and trend analysis | 
| Scikit-learn | Machine learning model development and evaluation | 
| SQL | (Optional) For data querying and transformation | 
| Excel | Basic data exploration for beginners | 

Objectives
- Analyze trends in medal distribution by year, country, and sport
- Identify top-performing countries and athletes
- Examine gender representation across Olympic disciplines
- Build a logistic regression model to predict medal winners

Exploratory Data Analysis
- Medal Trends Over Years: Line chart of total medals per year
- Top Countries: Bar chart of medal count by country
- Gender Participation: Pie and horizontal bar charts
- Event Diversity: Breakdown of unique Olympic events by sport
- Top Athletes: Ranking athletes by total medals won

Machine Learning (Logistic Regression)
Goal: Predict whether an athlete will win a medal based on:
- Country
- Sport
- Gender
- Event Gender
Workflow:
- Encode categorical variables using LabelEncoder
- Split dataset into training/testing sets
- Train and evaluate using LogisticRegression
- Use accuracy_score, confusion_matrix, and classification_report for performance

Advanced Analytics
Additional questions explored:
- Which country dominated a specific sport?
- Has any athlete won medals in multiple disciplines?
- Performance trends of top 5 countries over time


**IBM HR Analytics: Employee Attrition & Performance**

A data-driven HR analytics project exploring the key factors influencing employee turnover, satisfaction, and performance. Leveraging Python, SQL, and machine learning, the project provides actionable insights into workforce dynamics using a fictional dataset developed by IBM data scientists.

Tools & Technologies
| Tool/Tech | Functionality | 
| Python (Pandas, NumPy) | Data manipulation, wrangling | 
| Matplotlib & Seaborn | Visual analysis & storytelling | 
| Scikit-learn (Logistic Regression) | Predictive modeling | 
| SQL & Excel | Optional preprocessing & exploration | 

Project Objectives
- Analyze attrition rate by job roles, departments, education levels, and satisfaction metrics
- Identify major factors contributing to employee turnover (income, job satisfaction, etc.)
- Calculate average tenure and workforce stability
- Build a logistic regression model to predict attrition probability

Exploratory Data Analysis (EDA)
- Distribution of attrition by age, gender, and department
- Attrition patterns correlated with:
- Environment satisfaction
- Job involvement and performance rating
- Work-life balance and stock options
- Salary and promotion history

Machine Learning Modeling
Model Used: Logistic Regression
Target Variable: Attrition (Yes/No)
Steps:
- Data cleaning & encoding of categorical features
- Train-test split for model evaluation
- Model training & prediction
- Accuracy, confusion matrix, and classification report used for evaluation

Key Insights
- Attrition rate is ~16%, indicating moderate turnover
- Average employee tenure before leaving: ~7 years
- High attrition associated with:
- Lower satisfaction scores
- Less stock options and limited promotions
- Longer commuting distances


**Stock Market Analysis – Tech Giants Edition**

A comparative analytics and machine learning project analyzing historical stock data for Apple, Microsoft, Netflix, and Google. This project demonstrates financial data preprocessing, trend detection, and predictive modeling using Python, SQL, and Excel.

Tools & Technologies
| Tool/Tech | Purpose | 
| Python (Pandas, NumPy) | Data cleaning, wrangling, and analysis | 
| Matplotlib, Seaborn | Data visualization and trend mapping | 
| SQL & Excel | Preliminary data exploration | 
| Scikit-learn | Predictive modeling (Regression) | 
| Keras (optional) | Deep learning architecture (experimental) | 


Project Objectives
-  Load and inspect historical stock prices (3 months) for AAPL, MSFT, NFLX, and GOOG
-  Visualize market behavior and highlight company-specific volatility
-  Calculate moving averages, standard deviations, and daily returns
-  Analyze inter-stock correlations to identify co-movement and dependencies
-  Apply regression models to predict market size or price movements

Exploratory Data Analysis (EDA)
- Ticker Trends: Volume traded vs closing price per stock
- Statistical Summary: Mean, min, max values for Open, High, Low, Close prices
- Correlation Matrix: Heatmap showing relationships between price variables and volume
- Date Parsing & Time-Series Analysis: Convert to datetime format for smoother plots

Predictive Modeling (ML)
Target Examples:
- Market Size prediction using financial indicators
- Price volatility modeling
Techniques Used:
- Linear Regression
- Feature normalization (StandardScaler)
- Label encoding for categorical variables
- Model evaluation: MSE, R² Score
Optional:
- Deep learning workflow using Keras Sequential Model with Dropout layers
- Integration with APIs for real-time data ingestion

Key Visuals
- Boxplot of closing prices
- Volume vs Price scatter plots
- Moving average overlays
- Heatmaps for correlation and performance divergence





