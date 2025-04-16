# Task5_ElevateLabs

Dataset Overview

The dataset has 891 rows, each one representing a person and 12 columns, each one representing a feature of people.

Information like Name, Age, Sex, Ticket, Fare, Class (Pclass), and whether the person Survived or not is contained in the dataset.<br>


Missing Data

There are 177 missing values in age variable, we need to fill/handle these before modeling.

Cabin has 687 missing values, that is a lot—it might be dropped or handled carefully.

Embarked possesses 2 missing values. This is considered to be a negligible number. It should be easy to rectify<br>

Categorical Feature Insights

Gender: There are 577 men and 314 women. Only 314 women are fewer.<br>

Embarked (port where passenger got on):<br>

S = 644 people (most common)<br>

C = 168 people<br>

Q = 77 people<br>

Numerical Feature Relationships<br>

There is a high negative relationship between fare and Pclass, at a strength of -0.55. Typically the higher the fare, the higher the class.<br>

Survived positively correlates with Fare (0.26) so that people who paid more were more likely to survive.<br>

Pclass and Survived are negatively correlated at a value of -0.34 meaning that higher class passengers survival rate was higher.<br>

Regarding the variable "Age", the correlation with "Survived" is weak; the value (−0.07) is close
