# Project-2-Titanic-Dataset
###### By James Tooles
## Introduction
## The Purpose of Investigation

This project will conduct data analysis and create upon the 'Titanic Data' provided by Kaggle. The project will use Pandas and NumPy to attempt to answer and obtain insight into the questions below. 
* **For full analysis of the Titanic Data, please see 'Project 2 Investigate a Dataset.ipynb'.**

Question, Wrangle, Explore, Draw Conclusions, Communicate

## The Questions to Answer

1. What economic classes were most likely to survive?
2. What economic classes were most likely to not survive?
3. Were males or females more likely to survive?

## The Titanic Dataset

This dataset was provided by Udacity and was obtained from Kaggle. The feature descriptions are listed below for the ['Titanic Data'](https://d17h27t6h515a5.cloudfront.net/topher/2016/September/57e9a84c_titanic-data/titanic-data.csv). To view the source of the dataset please see the following link as provided by [Kaggle](https://www.kaggle.com/c/titanic/data)

#### VARIABLE DESCRIPTIONS:

* survival - Survival (0 = No; 1 = Yes)
* pclass - Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
* sex - Sex
* age - Age
* sibsp - Number of Siblings/Spouses Aboard
* parch - Number of Parents/Children Aboard
* ticket - Ticket Number
* fare - Passenger Fare
* cabin - Cabin
* embarked - Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

#### SPECIAL NOTES:
* Pclass is a proxy for socio-economic status (SES) 1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower


* Age is in Years; Fractional if Age less than One (1) If the Age is Estimated, it is in the form xx.5


* With respect to the family relation variables (i.e. sibsp and parch) some relations were ignored.  The following are the definitions used for sibsp and parch.
    
    
* Sibling:  Brother, Sister, Stepbrother, or Stepsister of Passenger Aboard Titanic
* Spouse:   Husband or Wife of Passenger Aboard Titanic (Mistresses and Fiances Ignored)
* Parent:   Mother or Father of Passenger Aboard Titanic
* Child:    Son, Daughter, Stepson, or Stepdaughter of Passenger Aboard Titanic


* Other family relatives excluded from this study include cousins, nephews/nieces, aunts/uncles, and in-laws.  Some children travelled only with a nanny, therefore parch=0 for them.  As well, some travelled with very close friends or neighbors in a village, however, the definitions do not support such relations.

## Conclusions
1. What economic classes were most likely to survive?
    * Overall, Class 1 passengers had the most survivors, shown in graph 'Titanic Survivors vs Deaths for Each Social-Economic Class'.
    * If the passenger was in Class 1, they had a 62.96% chance of surviving.
    * If the passenger was in Class 2, they had a 47.28% chance of surviving.
    * If the passenger was in Class 3, they had a 24.24% chance of surviving.
2. What economic classes were most likely to not survive?
    * Overall, Class 3 passengers had the most deaths, shown in graph 'Titanic Survivors vs Deaths for Each Social-Economic Class'.
    * If the passenger was in Class 3, they had a 75.76% chance of dying.
    * If the passenger was in Class 2, they had a 52.72% chance of dying.
    * If the passenger was in Class 1, they had a 37.04% chance of dying.
3. Were males or females more likely to survive?
    * Overall, female passengers had the most survivors, shown in graph 'Survivors - Male v Female'.
    * If the passenger was female, they had a 74.2% chance of surviving.
    * If the passenger was male, they had a 18.89% chance of surviving.
    
### Thoughts
The economic classes seem to have played a role in whether a passanger survived the Titanic crash. This could be due to the fact that the lower economic class, the worse the cabin purchased within the Titanic, which would result in being located on a lower deck. The flooding of the Titanic started at the lower decks and the water worked its way up into the ship. The passangers who were on the upper decks were also closer to the escape vessals, which could have given them the first choice of escape vessals and survivial. 

The sex of the passanger seemed to have played an extreme role in whether a passanger survived the Titanic crash. This could be due to the fact that women and childern were allowed to board the escape vessals first. This would have allowed women passangers to have had first choice of escape vessals and survivial.  

**All of there thoughts are speculation drawn from the known facts of the Titanic and the data given within the Kaggle Titanic dataset. There could be other factors which are not reflected in the dataset nor known from outside obervations and records.**

## References
* [Titanic Dataset](https://d17h27t6h515a5.cloudfront.net/topher/2016/September/57e9a84c_titanic-data/titanic-data.csv)
* [Kaggle: Titanic: Machine Learning from Disaster - Dataset Description and Details](https://www.kaggle.com/c/titanic/data)
* [Udacity: Investigate a Dataset - Project Rubic](https://review.udacity.com/#!/rubrics/107/view)
