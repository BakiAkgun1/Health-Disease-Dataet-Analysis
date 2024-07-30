# Health Disease Dataset Analysis
This project involves the analysis of the Health Disease dataset, focusing on various statistical tests and visualizations to understand the relationships between different features and the presence of heart disease.

## Visualizations

Pairplot
Visualized the relationships between age, chol, sex, and target (heart disease presence).

Age Histogram
Displayed the distribution of ages in the dataset.

Heatmap
Showcased the correlation between features in the dataset.

![Screenshot 2024-07-30 181829](https://github.com/user-attachments/assets/58e39543-d9b5-4451-acb4-8a928651e551)
![Screenshot 2024-07-30 181821](https://github.com/user-attachments/assets/04a8a5da-b2de-40c8-af2c-6db133ae0dc5)
![Screenshot 2024-07-30 181814](https://github.com/user-attachments/assets/f6b9efe7-01d7-481d-8aa7-a05b39c1e8d6)


# Statistical Tests
##  Normality Tests

## Shapiro-Wilk Test for Age
Statistic: 0.9844

p-value: 5.0416e-09

Interpretation: The age data significantly deviates from a normal distributio
.
## D'Agostino's K^2 Test for Cholesterol
Statistic: 236.9045

p-value: 3.6044e-52

Interpretation: The chol data significantly deviates from a normal distribution.

## Anderson-Darling Test for Age
Statistic: 5.8272

Critical Values: [0.574, 0.653, 0.784, 0.914, 1.088]

Significance Levels: [15%, 10%, 5%, 2.5%, 1%]

Interpretation: The age data does not follow a normal distribution at all tested significance levels.

## ANOVA (Analysis of Variance)
F-statistic: 56.7851

p-value: 1.0677e-13

Interpretation: There is a significant difference in some feature means with respect to the target variable.

## T-Test
T-Test for Age and Heart Disease Presence

t-Statistic: -7.5356

p-value: 1.0677e-13

Interpretation: There is a significant difference in the average age between those with and without heart disease.

## Chi-Square Test for Gender and Disease Presence
Chi-Square Stat: 78.8631

p-value: 6.6568e-19

Interpretation: There is a significant association between gender and the presence of heart disease.

## Kruskal-Wallis Test for Cholesterol Levels
Statistic: -4.5484e-13

p-value: 1.0

Interpretation: There is no significant difference in cholesterol levels between different heart disease statuses.

## Mann-Whitney U Test for Cholesterol Levels and Heart Disease Presence
U-Statistic: 138338.0

p-value: 1.0

Interpretation: There is no significant difference in cholesterol levels between groups with and without heart disease.

## Conclusion
The analysis reveals significant insights into the distribution of age and cholesterol levels concerning heart disease presence. Notably, age shows a significant deviation from normality, and there is a significant relationship between gender and heart disease presence.

