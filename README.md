# -JanataHack---E-Commerce-Analytics-ML-Hackathon
To support Janata Curfew announced by Honorable Prime Minister Narendra Modi, we announced JanataHack - a knowledge competition on Machine Learning &amp; Data Science on 22nd March 2020.   Looking at the immense response and public demand here we are back again with the second JanataHack, this time on E-Commerce Analytics.

Gist about data:
Two files were provided:- 
(1) training.csv - Columns provided: session_id, startTime, endTime, ProductList, gender

(2) testing.csv - Columns provided: session_id, startTime, endTime, ProductList

Agenda is to predict gender given startTime, endTime and ProductList used by a customer. ProductList contains multiple products differentiated by a semicolon(;) and the hierarchy of a product differentiated by (/). 

I have feature engineered the `train.csv` file data to `train_processed.csv` file which I have processed using the Jupyter notebook for a `Accuracy of 90%` on the training data. Due to submission not being on time, I cannot determing my score compared to others who had participated. 
