# NanoProject4

<li><a href="#Installation">Installation</a></li>
<li><a href="#Project Motivation">Project Motivation</a></li>
<li><a href="#File Descriptions">File Descriptions</a></li>
<li><a href="#Results">Results</a></li>
<li><a href="#Licensing, Authors, and Acknowledgements">Licensing, Authors, and Acknowledgements</a></li>

<a id='Installation'></a>
# Installation:
Python versions 3.*.
Libraries:
- Pandas
- Scikit-learn
- numpy
- matplotlib
- seaborn
- math
- json


<a id='Project Motivation'></a>
# Project Motivation:
This is a part of the Udacity Data Science NanoDegree. 
The task at hand was to use the datasets provided by Starbucks to find some insights into the appeal of their promotional offers. 
I tried to figure out which offers are the most attractive for the customers by analyzing the data.
There are several types of promo offers available for Starbucks clients. With the help of the provided data, we need to find out which type of offer is the most appealing and which customer group is more likely to profit from the promotional offers. 
We need to find out the relations between customers’ characteristics (age, gender, income, etc) and their willingness to take advantage of the offer.


<a id='File Descriptions'></a>
# File Descriptions:
For this project, I had three available datasets in a form of .json files:
- portfolio.json
- profile.json
- transcript.json
-

Portfolio.json contains the data about the offers — their types, duration, etc.
Profile.json contains information about the users — their gender, age, income and the time when they became the member.
Transcript.json is basically a log of transaction and offer completions. Unfortunately this file is too big to upload it on github, therefore I uploaded it to WeTransfer: https://we.tl/t-1rvf9FhQtq
Please download the file and put it in the data folder before running my code.
The code is stored in the following file:
- Starbucks_Capstone_notebook-ver2.ipynb

<a id='Results'></a>
# Results:

The analysis has produced some interesting results. I was surprised to see that women are more likely to benefit from the offer - I presumed it would be more equally distributed between the genders. I was also really surprised to see that the richest group of the Starbucks app has a pretty high offer completion rate.
I am pleased with the scores of the model I chose. Almost 88% accuracy with the .2 test set is not a bad score at all.
As for possible improvements, I think the model could be improved further if we work on the Train/Split some more. It's possible that different encoding of the values from 'age_group' and 'income_group', as well as normalizing the values in the whole set, could potentially improve the model. Using the MinMaxScaler could be a good idea.
The blog post about my findings can be found [here](https://lordmikis.medium.com/whats-starbucks-deal-f1499dc3d8e7).

<a id='Licensing, Authors, and Acknowledgements'></a>
# Licensing, Authors, and Acknowledgements:
I would like to thank Udacity and Starbucks for this great oportunity. Also, I would like to give special thanks to Udacity mentors who helped me when I got stuck.
