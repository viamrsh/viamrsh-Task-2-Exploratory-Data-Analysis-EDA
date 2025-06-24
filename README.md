# Task-2-Exploratory-Data-Analysis-EDA

1.Generate summary statistics (mean, median, std, etc.).

2.Create histograms and boxplots for numeric features.

3.Use pairplot/correlation matrix for feature relationships.

4.Identify patterns, trends, or anomalies in the data.

5.Make basic feature-level inferences from visuals.
# Objective: 
Understand data using statistics and visualizations.

# Tools:
Pandas, Matplotlib, Seaborn, Plotly

# code explanation 

1. Import Libraries

Load essential libraries for data analysis and visualization: pandas, numpy, matplotlib, seaborn, and plotly.



2. Load Dataset

Read the Titanic CSV file into a DataFrame.



3. Display Initial Data

View the first few rows to get a quick overview of the dataset.



4. Check Dataset Info

Print data types, non-null counts, and overall structure using .info().



5. Summary Statistics

Use .describe() to get statistical summaries like mean, median, std, min, and max.



6. Check Missing Values

Identify columns with missing data and how many values are missing.



7. Histograms for Numerical Columns

Visualize the distribution of each numeric feature (e.g., Age, Fare).



8. Boxplots for Outlier Detection

Use boxplots to identify outliers in numerical columns.



9. Correlation Matrix

Generate a heatmap to explore the relationships and strength of correlation between numeric features.



10. Pairplot Visualization



Use scatter plots and histograms to visualize pairwise relationships among numerical features.


11. Interactive Visualizations (Plotly)



Create interactive histograms to visualize how survival is related to Age and Sex.


12. Basic Feature-Level Inferences



Derive key insights such as:

Percentage of passengers who survived.

Survival distribution by gender.

Distribution of passengers by class (Pclass).


