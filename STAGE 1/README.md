## Data Preprocessing

### Handle Missing Values:
- [x] Identify columns with missing values.
- [x] Decide on a strategy to handle missing values (e.g., fill with median, mean, mode, or drop rows/columns).

### Encode Categorical Data:
- [ ] Identify categorical columns.
- [ ] Convert categorical columns to numerical format using techniques like Label Encoding or One-Hot Encoding.

### Feature Scaling:
- [ ] Identify numerical columns that need scaling.
- [ ] Apply scaling techniques like StandardScaler or MinMaxScaler.

## Exploratory Data Analysis (EDA)

### Understand Your Data:
- [ ] Get a summary of the dataset (e.g., `df.info()`, `df.describe()`).
- [ ] Check for any anomalies or inconsistencies in the data.

### Correlations:
- [ ] Calculate the correlation matrix.
- [ ] Visualize the correlation matrix using a heatmap.

### Distributions:
- [ ] Visualize the distribution of key features like `Age`, `Fare`, etc.
- [ ] Check for skewness or outliers in the distributions.

### Feature Relationships:
- [ ] Explore the relationship between `Pclass` and `Survived`.
- [ ] Explore the relationship between `Sex` and `Survived`.
- [ ] Explore the relationship between `Age` and `Survived`.
- [ ] Explore the relationship between `Fare` and `Survived`.
- [ ] Explore the relationship between `Embarked` and `Survived`.

## Questions to Answer

### Data Preprocessing:
- Which columns have missing values, and how many missing values are there?
- What strategy will you use to handle missing values for each column?
- Which columns are categorical, and how will you encode them?
- Which numerical columns need scaling, and what scaling technique will you use?

### Exploratory Data Analysis (EDA):
- What are the basic statistics (mean, median, mode, etc.) for numerical columns?
- Are there any correlations between features that stand out?
- What does the distribution of `Age` look like? Are there any outliers?
- What does the distribution of `Fare` look like? Are there any outliers?
- How does the survival rate vary across different passenger classes (`Pclass`)?
- How does the survival rate vary between males and females (`Sex`)?
- How does the survival rate vary across different age groups?
- How does the survival rate vary with the fare paid?
- How does the survival rate vary across different embarkation points (`Embarked`)?