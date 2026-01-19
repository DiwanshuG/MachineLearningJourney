## machine learning development life cycle [MLDC/MLDLC]

sdlc (software development life cycle)

1) Frame the Problem 

aapko kuch chije decide krni hoti hain before making a product
you can not start from scratch again and again{can't change the plan } even you are working on a small product 

but in real life it become more important to frame the problem accurately 

ki future me kya krna hota 


2) Data collection 

data is not easy available when you are working in real life

API -> JSON -> CSV file

web scraping

<!-- Trivago is a metasearch engine for hotels, meaning it doesn’t own hotel data itself but collects hotel listings and price offers from lots of other booking websites and shows them in one place. -->

Database -> Data warehouse [extract transform load]

sparks tools has the data


3) Data Preprocessing
noisy 
outlier
not compatible


remove duplicate
remove or treat missing values 
remove the outlier


4) EDA (exploratory data analysis)

experiment with data
find the info from data
univariate analysis
Vizualization
multivariate analysis
outlier detection
inbalance data treatment

[concrete] idea of data {find krna hota hai}

5) Feature ENgineering & Selection 

Input bnana

new columns cration (using big brain)

intelligence changes in data


<!-- Feature selection is the process of choosing the most relevant input variables (features) for building a machine learning model.
The goal is simple: use fewer, better features to get better performance. -->



6) Model Training ,Evaluation & Selection

train on different types of algorithms

<!-- performance matrices -->

selection
Feature selection means choosing the most important features from your dataset and discarding irrelevant or redundant ones—without creating new features.

<!-- Ensemble learning combines multiple models to make a stronger, more accurate prediction than any single model alone.

👉 Wisdom of the crowd, but for ML models. -->



7) Model Deployement 

Model se Binary files bna lete ho [pickle tool]  -> API -> JSON 


user input -> server ko milega -> prediction 


aws / gcp / heruko


8) Testing 

beta testing {loyal customer ke paas feature}

A/B testing 

9) Optimizing

-> Backup
-> Data
-> Load Balancing
-> Retrain model



model ko rotting se bachana
mask detection system : naye mask ke sath hame model ko train krna pdega 



