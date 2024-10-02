# The Boston Housing Dataset

The Boston Housing Dataset is derived from information collected by the U.S. Census Service concerning housing in the Boston, MA area. It is commonly used in machine learning and statistics for predicting house prices based on various features. Below is a description of each column in the dataset:

## Column Descriptions

- **CRIM**: Per capita crime rate by town.
  - This variable indicates the frequency of criminal activities in each town. A higher value suggests a higher crime rate, which may negatively affect housing prices.
  
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft.
  - This variable shows how much land in each town is designated for large residential properties. A higher value indicates more space for bigger homes, which can correlate with higher property values.

- **INDUS**: Proportion of non-retail business acres per town.
  - This variable represents the industrial activity in the area. Towns with higher industrial activity may have lower property values due to factors like pollution or noise.

- **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
  - This binary variable indicates whether the property is located next to the Charles River. Proximity to the river could increase property values due to the scenic view or potential for water-based activities.

- **NOX**: Nitric oxides concentration (parts per 10 million).
  - This measures air pollution levels in the area. Higher concentrations of NOX are often associated with lower air quality, which may lower housing prices.

- **RM**: Average number of rooms per dwelling.
  - This variable reflects the size of the homes in terms of the number of rooms. Larger homes tend to have higher property values.

- **AGE**: Proportion of owner-occupied units built prior to 1940.
  - This variable measures the age of homes in the area. A higher value suggests an older housing stock, which could either lower or increase home values depending on the condition and historical value of the homes.

- **DIS**: Weighted distances to five Boston employment centers.
  - This variable indicates how far the homes are from employment hubs. Homes located closer to job centers may have higher demand and thus higher prices.

- **RAD**: Index of accessibility to radial highways.
  - This measures how easily the town can access major highways. Better highway access usually increases the convenience for commuting and can raise property values.

- **TAX**: Full-value property-tax rate per $10,000.
  - This is the property tax rate in the area. Higher tax rates may either reflect better public services (which could increase property values) or discourage potential buyers (which could decrease values).

- **PTRATIO**: Pupil-teacher ratio by town.
  - This variable measures the quality of the education system, with lower values indicating more teachers per student. Areas with better education systems may have higher property values.

- **B**: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
  - This variable represents the proportion of the black population in the town. The formula applied here suggests it was included as part of an older socio-economic study on racial demographics and property values.

- **LSTAT**: Percentage of lower status of the population.
  - This measures the percentage of the population considered to be of lower socio-economic status. A higher percentage usually correlates with lower property values.

- **MEDV**: Median value of owner-occupied homes in $1000's.
  - This is the target variable in the dataset, representing the median home price in $1000s. This value is typically predicted using the other features in the dataset.

---

This dataset is often used in regression analysis to predict the median value of homes (`MEDV`) based on the other variables. By understanding the relationships between these features, you can make inferences about the factors that influence housing prices in Boston.
