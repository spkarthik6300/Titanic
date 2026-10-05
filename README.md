🚢 Titanic Dataset - Exploratory Data Analysis (EDA)
An end-to-end Exploratory Data Analysis (EDA) project on the famous Titanic dataset using Python, Pandas, Matplotlib, and Seaborn. This project explores key patterns, demographic factors, and socio-economic variables affecting passenger survival.

📌 Project Overview
The objective of this project is to clean, analyze, and visualize passenger data to uncover key insights, such as:

Impact of passenger class (Pclass) and ticket fare on survival.
Survival trends across genders and different age groups (Child, Adult, Old).
Data distributions and relationships among key demographic attributes.
🛠️ Tech Stack & Libraries
Language: Python
Data Manipulation: pandas, numpy
Data Visualization: matplotlib.pyplot, seaborn
Environment: Jupyter Notebook
🔄 Workflow & Analysis Steps
1. Data Understanding & Inspection
Inspected dataset shape (891 rows, 12 columns) and column data types.
Checked statistical summaries (df.describe()) and overall structure (df.info()).
2. Data Cleaning & Preprocessing
Missing Values Handling:
Dropped the Cabin column due to high missing values.
Imputed missing values in Age using the mean.
Imputed missing values in Embarked using the mode.
Inspected numeric columns for outliers.
3. Feature Engineering & Binning
Grouped passengers into custom age buckets using pd.cut():
Child: 0–18 years
Adult: 18–40 years
Old: 40–70+ years
4. Dashboard & Visualizations
Created a multi-panel visualization dashboard covering:

Survival Rate by Age Group: Comparison of survival rates across age categories.
Survival Rate by Gender: Pie chart highlighting female vs. male survival distribution.
Survival Rate by Pclass: Horizontal bar chart showing survival probability across classes.
Passenger Count by Pclass: Line plot illustrating the volume of passengers in 1st, 2nd, and 3rd class.
Age vs. Fare (Survival): Scatter plot analyzing the combined impact of age, ticket fare, and survival status.
Age Distribution: Histogram with KDE showing passenger age spread.
💡 Key Insights
Gender Disparity: Female passengers had a significantly higher survival rate (~79%) compared to male passengers (~20%).
Socio-Economic Class: Passengers traveling in 1st class had a much higher likelihood of survival compared to those in 3rd class.
Age Factor: Children showed higher survival rates compared to older age groups, aligning with the "women and children first" protocol.
