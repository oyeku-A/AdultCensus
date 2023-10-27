# :money_with_wings: Adult-Census-Income-Prediction
> Building a classification model for predicting the income of a person using the Adult Census Income Dataset.

## :clipboard: Overview:
> In this notebook, we are going to predict whether a person's income is above 50k or below 50k using various features like age, education,gender,country,race,etc.

## :bar_chart: Dataset:
| Column ID |   Column Name  | Data type | Values type |          Description         |
|:---------:|:--------------:|:---------:|:-----------:|:----------------------------:|
|     0     |       age      |   int64   |  Continous  |         Age of person        |
|     1     |    workclass   |   object  |   Discrete  |      Workclass of person     |
|     2     |     fnlwgt     |   int64   |  Continous  |         Final weight         |
|     3     |    education   |   object  |   Discrete  |  Education Degree of person  |
|     4     |  education.num |   int64   |  Continous  | Number of years of education |
|     5     | marital.status |   object  |   Discrete  |   Marital status of person   |
|     6     |   occupation   |   object  |   Discrete  |     Occupation of person     |
|     7     |  relationship  |   object  |   Discrete  |    Relationship of person    |
|     8     |      race      |   object  |   Discrete  |        Race of person        |
|     9     |       sex      |   object  |   Discrete  |         Sex of person        |
|     10    |  capital.gain  |   int64   |  Continous  |    Capital gain of person    |
|     11    |  capital.loss  |   int64   |  Continous  |    Capital loss of person    |
|     12    | hours.per.week |   int64   |  Continous  |   Number of hours per week   |
|     13    | native.country |   object  |   Discrete  |   Native country of person   |
|     14    |     income     |   object  |   Discrete  |   Income category of person  |

## :chart_with_upwards_trend: Data Analysis:
### :books: Dataset:

> - It contains categorical and numerical variables.
> - It is skewed and contains outliers.
> - It is not normally distributed.
> - It has "?" valyes for columns which need to be taken care of.

### :handshake: Relationships:
> - Relationships between various variables has been analysed and significant points have been highlighted.

## :memo: Motivation:
> - While working on the project, I discovered various social factors which affect the income of a person and indirectly hamper the growth of economy.
> - These factors, if paid attention to, by the concerned authorities & modified accordingly can contribute significantly to rise in economy of a country.

## :scroll: Conclusion:
> - In this project, various models like Random Forest Classifier,GaussianNB,DecisionTreeClassifier,Adaboost,Xgboost,LGBM.
> - Random forest classifier was the best fit for this dataset with an accuracy score of 91%.
