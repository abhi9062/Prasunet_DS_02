Titanic Data Analysis 
This script performs exploratory data analysis (EDA) on the Titanic dataset, including data cleaning, preprocessing, and visualization.

Data Loading
The script loads three datasets:

gender_submission.csv
train.csv
test.csv
Data Inspection
It displays the first few rows of the gender submission dataset to understand its structure.

Data Preprocessing
The script handles missing values by:

Filling missing Age values with the median.
Filling missing Embarked values with the mode.
Filling missing Fare values with the median.
Dropping the Cabin column due to many missing values.
Data Visualization
The script generates several plots to visualize data distributions and relationships:

Age Distribution: Histogram with KDE for the Age feature in the train dataset.
Gender Distribution: Count plot for Sex in the train dataset.
Passenger Class Distribution: Count plot for Pclass in the train dataset.
Age Distribution by Passenger Class: Box plot for Age by Pclass in the train dataset.
Survival Distribution: Count plot for Survived in the train dataset.
Age Distribution by Survival: Box plot for Age by Survived in the train dataset.
Survival by Passenger Class: Count plot for Survived by Pclass in the test dataset.
Survival by Gender: Count plot for Survived by Sex in the test dataset.
Correlation Heatmap: Heatmap of correlations among numeric features in the train dataset.
Pair Plot: Pair plot of numeric features in the test dataset, colored by Survived.
