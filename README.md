In this task, I worked on the famous Titanic dataset from Kaggle.
The goal was to:
	•	Clean the dataset by handling missing values and irrelevant columns.
	•	Perform Exploratory Data Analysis (EDA) to understand relationships between variables.
	•	Identify meaningful patterns and insights about survival chances on the Titanic.

⸻

📌 Approach / Steps Followed
	1.	Load the Dataset
	•	Used pandas to load the train and test datasets into Google Colab.
	•	Checked dataset shape, columns, and missing values.
	2.	Data Cleaning
	•	Filled missing Age values with the median.
	•	Filled missing Embarked values with the most common port (mode).
	•	Dropped the Cabin column (too many missing values).
	•	Filled missing Fare in the test dataset with median.
	3.	Exploratory Data Analysis (EDA)
	•	Survival Counts: Bar chart showing total survivors vs non-survivors.
	•	Survival by Gender: Compared male vs female survival rates.
	•	Age Distribution: Histogram showing age ranges of passengers.
	•	Fare vs Pclass: Boxplot to visualize how ticket prices varied by passenger class.
	•	Correlation Heatmap: Checked how numerical variables (Age, Fare, Pclass, SibSp, Parch) relate to survival.
	4.	Insights Found
	•	Women had a higher survival rate compared to men.
	•	First-class passengers survived more often than second or third class.
	•	Younger passengers (especially children) had higher chances of survival.
	•	Higher ticket fares were associated with better survival chances.

 📌 How to Run the Project/Code
	1.	Open Google Colab.
	2.	Upload train.csv and test.csv files (Titanic dataset).
	3.	Install required libraries if not already available:

    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns

  4.	Run the cleaning and visualization code (already explained in steps).
	5.	Outputs (plots/graphs) will be displayed inline in Colab.
