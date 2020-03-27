# unbalanced_classes_case_study
Unbalanced Classes Case Study

data: email.csv
notebook: unbalanced_classes_1.ipynb,unbalanced_classes_2.ipynb

The high high majority of real datasets are highly unbalanced. Typically, the minority class is between 1 and 3% for the most important metrics, i.e. conversion rate, ads click-through-rate, fraud, email click-rate.

Building a model with unbalanced data presents a few challenges. The biggest problem is that if you predict everything as majority class, you will get a huge accuracy. And many models internally are built to optimize accuracy. So feed into the model a dataset with 2% class 1 and 98% class 0, and you will get as an output a model that predicts (almost) everything as class 0 with ~98% accuracy. 98% accuracy might look good at first, but a model like that is hardly useful.

In these two notebooks I did some work on  how to handle this challenge
