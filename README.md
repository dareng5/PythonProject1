# PythonProject1


Selection

From the provided dataset, I selected “New Visions Charter High School Network” for my project. The network has four "Advanced Math and Science" high schools in total:

84X539 - New Visions Charter High School for Advanced Math and Science, Bronx
84X202 - New Visions Charter High School for Advanced Math and Science II, Bronx
84K738 - New Visions Charter High School for Advanced Math and Science III, Brooklyn
84Q320 - New Visions Charter High School for Advanced Math and Science IV, Queens

I prepared two piece of dataframe: "sch", which is pure filtering of the original dataset, and "schgrp", which is showing data on school level by summarizing all tests.

I looked at for things:
  A.  On class level,
    1.	Distribution of each classes’ mean score by school by year
    2.	Distribution of each classes’ percentage of students who scored 65 or above by school by year
  B.  On school level,
    1.	Each school’s mean score by year
    2.	Percentage of each school’s student who scored 80 or above by year

Observations

A1.
As the violin plot shows, all schools generally get "fatter" throughout the year, meaning the variation of the mean score among classes within the same school are getting smaller.

A2.
The swarm plot shows all classes are having a higher percentage of students scoring 65 or higher. In 2017, most of the classes in A.M.S. II and III have a higher percentage than the other two schools. It also shows that classes within the same school are "evening" their percentage throughout the years, as you can see in 2017 there are three "layers": A.M.S. II and III at around 80%, A.M.S. around 70% and A.M.S. IV around 60%.

B1.
The point plot shows that all schools except A.M.S. IV have their mean score improved throughout the years, with A.M.S improves gradually and A.M.S. II and III took a big jump in 2016.

B2.
The point plot shows that well-performed students in all schools except A.M.S. IV increases throughout the years. The result is similar to mean score while the schools are improving at a slower pace.
