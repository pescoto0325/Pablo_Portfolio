# Pablo's Data Science Portfolio
Data Science Projects

Hello there and welcome to my highlight reel for projects! 

## Project 1: [Data Science NLP LDA Model: Project Overview](https://github.com/pescoto0325/Pablo_Portfolio/blob/main/NLP%20LDA%20Model)
Texts have become one of the most ubiquitous forms of marketing data in the digital economy. Perhaps nowhere is this more salient than in the online reviews domain. In this module, we examined how natural language processing (NLP) techniques can be applied to Honda car reviews. This [dataset](https://www.kaggle.com/datasets/ankkur13/edmundsconsumer-car-ratings-and-reviews) is available in Kaggle and requires some cleansing and preparation beforehand.

Questions this project answers:
* Are the reviews usually fact or opinion based?
* What are some topics to think when buying a Honda vehicle?
* Are the topics correlating with the ratings?

![](Polarity.png) 
Based on the polarity of our data, our reviews are leaning more for the positive side. (0 = Bad and 1 = Good)
![](Subjectivity.png)
Based on the Subjectivity of our data, our reviews are mostly based on facts. (0 = Opinion and 1 = Facts)
![](LDA.png)
As we can see from our LDA visuals, our text analysis showcases what the most spoken and important words are and joins them into topics. As an example we see how vehicle is mentioned the most (Honda Analysis duh) and the Honda Odyssey seems to be most mentioned Model.

## Project 2: [Regression Analysis: Price per stat Model](https://github.com/pescoto0325/Pablo_Portfolio/blob/main/Price%20per%20stat%20Model)
Why are the bests players in real life not the most expensive players in the game?
In this analysis,  linear and logistic regression are used to understand the relationship between stats and in game price for all the players. The [dataset](https://www.kaggle.com/datasets/mohammedessam97/fifa-22-fut-players-dataset) shows the stats and in-game price for players in FIFA 22.

Questions this project answers:
* What stats have a higher impact on a players price?
* Is this relationship the same for all positions?
* Is there a clear winner across all of the stats?
![](Fifa%202022%20stats.png)
Our regression that weak foot is the stat that holds the higher impact across all positions, higher than pace.

## Project 3: [Conjoint Analysis: Feature importance in a product](https://github.com/pescoto0325/Pablo_Portfolio/blob/main/Conjoint%20Analysis)
Analysis which provides statistical evidence on which feature has a greater impact in ratings.

Using a [dataset](https://github.com/pescoto0325/Pablo_Portfolio/blob/main/motorbike_conjoint.csv) from a survey of motorcycles we dissect the importance of features in a product to understand what is best for the client. To do this, we use a hierarchical linear model (HLM) that estimates both the overall fixed effect and the individual level random effect.

Questions this project answers:
* What is the relative importance of a feature in a product?
* Which combination provides a better rating?
* How many different products can be made from a defined set of features?

![](Conjoint-Partworth.png) 
![](Conjoint-attimportance.png)
After some regression and HLM, we get to see that price has the biggest impact on a rating, either good or bad.
