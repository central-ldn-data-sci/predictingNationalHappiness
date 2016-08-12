# predictingNationalHappiness

We'll be using the World Development Indicator Dataset (WDI) to see which factors are most predictive of a nation's happiness score:

[About the Metric] (https://en.wikipedia.org/wiki/World_Happiness_Report). Can we learn more about what might predict this score other than the factors wikipedia has listed? Let's find out. 

Take the World Development Indicator Dataset (aka WDI) (which is available in both R and Python) and select some features you think would be most predictive of that happiness score - then give a go at modeling to predict national happiness. 

* [R package](https://github.com/vincentarelbundock/WDI)
* Integrated directly in the [Pandas library as an I/O module] (https://pypi.python.org/pypi/wbdata).

---

Goal: Using the WDI dataset, figure out which factors are most strongly predictive of well being in a given country - for example, is lack of debt predictive of a country’s happiness score?

Topics: Data Munging, Joining, Feature Selection, Modeling or Visualization

* I. Get the Well-Being Data - csv from github. Creat a dataswet with "country", and "happiness_score"
* II. Get the Other Features on a Country Level from the R or Python library 
R - WDI dataset 
WDI::WDIsearch() to see factors - look at the documentation to see how to look up the other factors
Python  instructions [here] (https://pypi.python.org/pypi/wbdata) 
* III. Join the two datasets on the country name. Your output should look like…
Country, happiness_score, feature_1, feature_2, etc where it’s up to you to select which features and how many to put into the dataset.

Potential Issues - joining on country name - it may not be the same string between the sets.

How you approach feature selection depends on what you want to focus on for the evening.
*  If you are less experienced, my recommendation would be to pick 2-3 features you think might be interesting and then run a multivariate linear regression on them. Focus on getting the mathematical concepts and the coding implementation (R, Python, etc) rather than making the perfect model. Alternatively, you could focus on visualization, and, although this isn't modeling directly, it will help you understand which features you may want to use if you did want to model it - download Tableau Public and pop the csv in to see what you learn. 
* If you are more experienced, it’s totally up to you how you approach the problem! Some ideas: (1) Practice a skill you want to improve at - for example, if you are usually a model-er, try doing a visualization approach, etc. If you usually use R, try python, etc. A new model you haven’t done, etc. (2) If mentoring is your interest (teaching helps you solidify learning), help out one of the n00bs.

Note we probably won’t finish this problem tonight - 2 hours likely too short, but give it a go and see what you learn. Follow up after if you liked it. Feedback is welcome. 

Before you head out, take a few minutes to summarize how you approached the problem and then share with the group.For example…
* Did you use R or Python? 
* What libraries/packages/models? 
* Did you find any interesting insights? 
* What did you find most challenging? etc.


Bring: 

* Laptops, Charging Cords, an Inquisitive Spirit



