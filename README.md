# Bootstrap in R

# Project Summary

This repository hosts the R code and data file for bootstrapping. With a finite number of samples, the bootstrap method comes in handy and provides valid inferences about the population distribution. However, there are several pitfalls that beginners often fail to account for. 

Treating the NBA Game 6 between the Celtics and Heat as an example, I walk through the process of creating bootstrap samples along with the model interpretations. The entire write-up is available at <https://towardsdatascience.com/a-practical-guide-to-bootstrap-with-r-examples-bd975ec6dcea>.

## Installing

This project is conducted in the R environment, and you have to pre-install the boot library.

## What is the data?

This dataset is the last post-season game between two NBA teams -- Celtics and Heat -- at DraftKings. The dataset contains four variables: Player, Roster Position, %Drafted, and FPTS.

Player: NBA players' names

Roster Position: the position the player held in the DraftKings lineups, whether as Captain (CPT) or Utility (UTIL). DraftKings has a 1.5 multiplication power over the captain. 

%Drafted: the percentage of people drafted this player

FPTS: Fantasy Points 

This project focuses on the last two variables -- %Drafted and FPTS -- and tries to understand how strongly they correlate with repeated samplings.

## About the Author

Leihua Ye is a Ph.D. Researcher at the UC, Santa Barbara. He has received extensive training in Causal Inference, Research Design, Machine Learning, Big Data, and Machine Learning. 

He receives his B.A. and M.A. from the Uni. of Nottingham. 

## Contact

Email: yeleihua@gmail.com

LinkedIn: www.linkedin.com/in/leihuaye

Tech Blog: https://leihua-ye.medium.com
