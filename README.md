# predictingNationalHappiness

We'll be using the World Development Indicator Dataset (WDI) to see which factors are most predictive of a nation's happiness score:

[World Happiness Report](https://en.wikipedia.org/wiki/World_Happiness_Report)

The WDI dataset is available both as an [R package](https://github.com/vincentarelbundock/WDI), and integrated directly in the [Pandas library as an I/O module] (http://pandas-docs.github.io/pandas-docs-travis/#world-bank).

---

Topics: Data Munging, Feature Selection, Modeling or Visualization

Bring: 

* Laptops, Charging Cords, an Inquisitive Spirit

Pre-Requisites: 

* Familiar with either R or Python 

---

Goal: Using the WDI dataset, figure out which factors are most strongly predictive of well being in a given country - for example, is lack of debt predictive of a country’s happiness score?

Topics: Data Munging, Joining, Feature Selection, Modeling or Visualization
Slack Chat - https://central-ldn-data-sci.slack.com/messages/general/ 

* I. Get the Well-Being Data - csv from github
* II. Get the Other Features on a Country Level 
R - WDI dataset 
WDI::WDIsearch() to see factors - look at the documentation to see how to look up the other factors
Python  instructions here 
III. Join the two datasets on the country name. Your output should look like…
Country, happiness_score, feature_1, feature_2, etc where it’s up to you to select which features and how many to put into the dataset.

Potential Issues - joining on country name - it may not be the same string between the sets.

How you approach feature selection depends on what you want to focus on for the evening.
If you are less experienced, my recommendation would be to pick 2-3 features you think might be interesting and then run a multivariate linear regression on them. Focus on getting the mathematical concepts and the coding implementation (R, Python, etc) rather than making the perfect model. Alternatively, you could focus on visualization - download Tableau Public and pop the csv in to see what you learn. 
If you are more experienced, it’s totally up to you how you approach the problem! Some ideas:
Practice a skill you want to improve at - for example, if you are usually a model-er, try doing a visualization approach, etc. If you usually use R, try python, etc. A new model you haven’t done, etc. 
If mentoring is your interest (teaching helps you solidify learning), help out one of the n00bs.

Note we probably won’t finish this problem tonight - 2 hours likely too short, but give it a go and see what you learn. 

Before you head out, take a few minutes to summarize how you approached the problem and then share with the group.For example…
* Did you use R or Python? 
* What libraries/packages/models? 
* Did you find any interesting insights? 
* What did you find most challenging? etc.



