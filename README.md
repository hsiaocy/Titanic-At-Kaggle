<h1>Titanic-at-Kaggle</h1>

<hr>

This is a practice on the [competition on Kaggle](https://www.kaggle.com/c/titanic/overview).

This competition provides three csv files(train.csv, test.csv, gender_submission.csv(sample))

The Titanic passengers data (train.csv & test.csv) tell us:
|   Attribute | Definition                                                          |
|-------------|---------------------------------------------------------------------|
|         Age | Age in years                                                        |
|       Cabin | Cabin number                                                        |
|    Embarked | Port of Embarkation(C = Cherbourg, Q = Queenstown, S = Southampton) |
|        Fare | Passenger fare                                                      |
|        Name |                                                                     |
|       Parch | # of parents / children aboard the Titanic                          |
| PassengerId |                                                                     |
|      Pclass | Ticket class(1 = 1st, 2 = 2nd, 3 = 3rd)                             |
|         Sex | Gender                                                              |
|       SibSp | # of siblings / spouses aboard the Titanic                          |
|    Survived | Survival(0 = No, 1 = Yes)                                           |
|      Ticket | Ticket number                                                       |


We need to give a prediction data (submission.csv) that includes:
| PassengerID | Survived                                                            |
|-------------|---------------------------------------------------------------------|
|           # | 0 or 1                                                              |

<hr>

*Features*: *Feature engineering*, *Supervised Learning*.

Reference: [[資料分析&機器學習] 第4.1講 鐵達尼號災難生存預測](https://gist.github.com/yehjames/8c0e552975c876eb289d6b03d9d00ca4#file-4-1-ipynb)
