# Python-practice
Data Analysis Internship Task 5
# Task 5: Exploratory Data Analysis (EDA)

## 🎯 Objective
Perform Exploratory Data Analysis (EDA) on a structured dataset to extract key insights using statistical summaries and visualizations.

## 📦 Dataset
- **Source:** [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data?select=train.csv)
- **Files Used:** `train.csv`
- Alternatively, you may use any relevant dataset of your choice.

## 🛠️ Tools & Libraries
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## 📌 EDA Techniques Applied
### ✅ Data Exploration
- `df.head()`, `df.info()`, `df.describe()`
- Missing value analysis
- Value counts for categorical variables

### 📊 Visual Analysis
- **Univariate Analysis:**
  - Histograms, Countplots
- **Bivariate Analysis:**
  - Boxplots, Violin plots
  - Grouped bar charts
- **Multivariate Analysis:**
  - Pairplots
  - Correlation heatmaps

### 📉 Statistical Insights
- Distribution of age, fare
- Survival rates based on sex, class, and embarkation point
- Correlation between numerical features

## 📈 Key Visuals
- `sns.heatmap()` to show correlations
- `sns.pairplot()` for multivariate relationship exploration
- Boxplots for age vs survival
- Countplots for class and gender distributions

## 🧠 Observations & Insights
- Females had a significantly higher survival rate than males.
- Passengers in 1st class were more likely to survive.
- Younger passengers had higher survival probabilities.
- Strong correlation between Pclass and Fare.
- Some missing values in `Age` and `Cabin`.

## 📋 Summary
The EDA provided clear patterns in the Titanic dataset regarding how factors such as **gender**, **age**, and **passenger class** influenced survival. These insights can be used to build predictive models or deepen our understanding of real-world social and economic factors in historical events.

## 📂 Project Structure
