📂 Project Structure
EDA_Task.ipynb → Main Jupyter Notebook containing all data cleaning, analysis, transformations, and visualizations.

📚 Dataset Information
PassengerId: Unique ID of each passenger

Survived: Survival (0 = No, 1 = Yes)

Pclass: Passenger Class (1st, 2nd, 3rd)

Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

The project involved multiple tables:

One table containing Passenger details

One table containing PassengerId and Survived status

Another table containing all columns

🔍 Work Done
Table Joining: Merged the Survived information to the main dataset using PassengerId as a reference.

Handling Missing Values:

Imputed numeric missing values using median.

Imputed categorical missing values using mode.

Duplicate Checking: Used .nunique() and manual inspection.

Fare Analysis:

Initial Fare distribution was highly skewed with extreme outliers.

Applied log transformation to normalize Fare values and improve visualization.

Correlation Analysis:

Used a heatmap to uncover correlations.

Observed strong relations between Fare and Survival.

Survival Analysis:

Analyzed survival rates by Sex, Passenger Class, and combinations of both.

🧪 Application of Log Transformation
The Fare feature exhibited extreme right skewness due to a few very high values.
To address this:

Log transformation was applied to the Fare column.

Benefits:

Reduced skewness and normalized the distribution.

Made patterns more interpretable.

Helped reveal meaningful trends when grouped by class.

📈 Key Findings
Higher fares were associated with a higher survival probability.

First-class passengers survived at significantly higher rates compared to 2nd and 3rd class.

Female passengers had much better survival rates, supporting the historical account of "Ladies first" during evacuation.

The median Fare provided a better central tendency than the mean due to outliers.

🛠️ Technologies Used
Python (Pandas, NumPy)

Data Visualization (Matplotlib, Seaborn)

Jupyter Notebook