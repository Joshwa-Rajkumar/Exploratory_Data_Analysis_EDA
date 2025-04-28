# Exploratory_Data_Analysis_EDA

🔍 Analysis Performed

Checked for missing values and data types

Merged different tables using PassengerId

Survival rate analysis:

By Sex

By Passenger Class

By Sex + Passenger Class

Ticket Fare analysis:

Based on Pclass (Passenger Class)

Identified outliers and used Median instead of Mean

Applied Log Transformation to Fare for better visualization and analysis

🧪 Application of Log Transformation

The Fare feature had significant positive skewness due to a few extremely high ticket prices.

To handle this:

A logarithmic transformation was applied to the Fare values.

This helped to:

Normalize the distribution

Reduce the impact of outliers

Make patterns across classes clearer

✅ After log transformation, fare values were more balanced, helping better interpretation during analysis.

Visualizations:

Bar plots for survival rates

Bar plots for fare distributions

Heatmaps for combined survival rates


📈 Key Findings

Females had a much higher survival rate than males.

1st Class passengers had a significantly higher survival chance compared to 3rd class.

Fare prices were highly skewed; median fares represent better central tendency than mean.

Higher class passengers generally paid more and had better chances of survival.


🛠️ Technologies Used

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook
