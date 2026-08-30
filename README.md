# AI & ML Internship - Task 2: Exploratory Data Analysis (EDA)

## Objective

The objective of this task is to understand the dataset using statistics and visualizations.

## Dataset

The **Titanic Dataset** was used for this task.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Kaggle Notebook

## Exploratory Data Analysis Performed

### 1. Dataset Exploration

The Titanic dataset was imported and explored using:

- `head()`
- `shape`
- `info()`
- `describe()`
- Missing value analysis

### 2. Summary Statistics

Summary statistics were generated for numerical features, including:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Quartiles

The main numerical features analyzed were:

- Age
- Fare
- SibSp
- Parch

### 3. Histograms

Histograms were created to understand the distributions of numerical features.

The following features were visualized:

- Age
- Fare
- SibSp
- Parch

The histograms helped identify the shape of the distributions, concentration of values, and skewness.

### 4. Boxplots

Boxplots were created for numerical features to understand their distributions and identify potential outliers.

The following features were analyzed:

- Age
- Fare
- SibSp
- Parch

### 5. Correlation Analysis

A correlation matrix was calculated for numerical variables.

A correlation heatmap was created to visualize the relationships between features.

The following variables were included in the correlation analysis:

- Survived
- Pclass
- Age
- SibSp
- Parch
- Fare

### 6. Scatterplots

Scatterplots were used to investigate relationships between numerical features.

The following relationships were analyzed:

- Age vs Fare
- Fare vs Passenger Class

### 7. Survival Analysis

Survival patterns were explored using visualizations.

The analysis included:

- Survival count
- Survival by gender
- Survival by passenger class
- Survival rate by gender
- Survival rate by passenger class

### 8. Patterns, Trends and Anomalies

The visualizations were used to identify important patterns and anomalies in the dataset.

Some observations include:

- Gender showed an important relationship with survival.
- Passenger class was associated with survival.
- Fare showed a right-skewed distribution.
- Some numerical features contained potential outliers.
- Correlation analysis helped identify relationships between numerical variables.

## Key Insights

- Female passengers generally had a higher survival rate than male passengers.
- Passengers in higher classes generally had better survival rates.
- Fare values were not evenly distributed and contained some unusually high values.
- Boxplots helped identify potential outliers.
- Histograms helped understand the distribution of numerical features.
- The correlation heatmap helped visualize relationships between numerical variables.
- Data visualization made patterns and trends easier to identify.

## Repository Structure

```text
AI-ML-Internship-Task2-EDA/
│
├── README.md
├── task-2-eda.ipynb
└── Titanic-Dataset.csv
