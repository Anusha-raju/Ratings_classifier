# Ratings Classifier

***The aim of this project is to get meaningful insights in the review data and model a ML model to predict the ratings.***

The data is stored in 'googleplaystore.csv'

The data consists of *13 columns and 10841 rows.*

The columns are:

- App: Application name
- Category: Category the app belongs to
- Rating: Overall user rating of the app (as when scraped)
- Reviews: Number of user reviews for the app (as when scraped)
- Size: Size of the app (as when scraped)
- Installs: Number of user downloads/installs for the app (as when scraped)
- Type: Paid or Free
- Price: Price of the app (as when scraped)
- Content Rating: Age group the app is targeted at - Children / Mature 21+ / Adult
- Genres: An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
- Last Updated: Date when the app was last updated on Play Store (as when scraped)
- Current Ver: Current version of the app available on Play Store (as when scraped)
- Android Ver: Min required Android version (as when scraped)

*The data consists of missing values and invalid entries.*

There are categorical data as well.





### The observations that are drawn from EDA:

- What type of services people loves either paid or free??

- In which month Free/Paid apps added are most??

- Distributions of Ratings

- The category which has the most apps.

- Most preferred version of the apps

  

**The data is then cleaned, outliers are removed, the missing values are filled.**

**The categorical variables are then encoded using techniques like Mean encoding, Target guided encoding, Label encoding.**

*All the insignificant columns are then dropped.*







### The features that are considered for ML Modelling 



**[Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, year_added, month_added]**

*of which year_added, month_added are obtained from Last Updated*





- The Dependent Variable is : **Rating**

- The data is then split to Train and Test Data , where test data is 20%.



#### *This is a **Classification** problem*

#### Logistic Regression , Decision Tree, Random Forest are considered for Modelling

   *Respective stats are obtained.*

