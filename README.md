
# Titanic - Machine Learning from Disaster
## Links

 - [Kaggle project website](https://www.kaggle.com/competitions/titanic/data)
 - [Jason Chong You Tube project video, part 1/2](https://youtu.be/GSk-EEu1zkA)
 - [Jason Chong You Tube project video, part 2/2](https://youtu.be/i5E2hruuLaQ)


## Project decrtiption

1. Project is inspired by kaggle: **Titanic - Machine Learnicn from Disaster**. Data from folder _titanic_data_ was donwloaded directly from kaggle project website, contains the files:
* training.csv
* test.csv
* gender_submission.csv

2. Data set:
#### The data contain features:
|Feature|Definition|Key|
|---	|---	|---	|
|Survival|   Survival	|   	|
|Pclass|  Passanger ticket class 	|  1 = 1st, 2 = 2nd, 3 = 3rd 	|
|   Sex	|   Sex	|   	|
|   Age	|   Age in years 	|   	|
|   SibSp	|   # of siblings / spouses aboard the Titanic	|   	|
|   Parch	|   # of parents / children aboard the Titanic 	|   	|
|   Ticket	|   Ticket number 	|   	|
|   Fare	|   Passenger fare 	 	|   	|
|   Cabin	|   Cabin number  	|   	|
|   Embarked	|   Port of Embarkation 	|   C = Cherbourg, Q = Queenstown, S = Southampton	|



#### Extra description

**Pclass** : A proxy for socio-economic status (SES): 1st = Upper, 2nd = Middle, 3rd = Lower

**Age** : Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**SibSp** :
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

** Parch ** :
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

3. Goal

I created Machine Learninc model wich predict a survived posibility for the test dataframe.
## Run Locally

Clone the project

```bash
  git clone https://github.com/guzweronika/titanic_kaggle_ML_project.git
```

Go to the project directory

```bash
  cd titanic_kaggle_ML_project
```

Open jupyter notebook (for example via anaconda)

```bash
  jupyter notebook
```


