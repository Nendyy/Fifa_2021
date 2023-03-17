# Fifa_2021
#Data_cleaning_challenge


> The data Cleaning Challenge was organised on twitter by Promise Nonso and Victor Somadina in order to help data analysts train/improve on their data cleaning skills using any tool of their choice. It also provided an avenue for data analysts to meet and collaborate with other learners. The dataset for this challenge was sourced from kaggle and can be found [here](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring). 

### Some of the issues observed with the dataset include:

> 1. Many of the columns such as height, weight, value, wage etc were wrongly stored as string data type instead of integers, and this is because of the presence of alphabetical characters.
> 2. Some of the column names are not clear such POT, OVA etc and need to be renamed to enhance readability.
> 3. Some columns are not necessary/needed for analysis hence they should be dropped.
> 4. The club column contains '/n/n/n' which needs to be striped off, same as W/F, SM and IR columns which contain the star symbol.
> 5. Input the correct datatypes for columns such as contract date, joined etc.
> 6. Height column records height of some players in cm and others in feet/inches.It should be converted to one standard measurement.
> 7. Weight column contains players weights in both kilogram and pounds,this should also be converted to one standard measurement.
> 8. Wage, Release clause and Value columns contains euro sign which should be removed, it also lists the ammount in M (for million)and K (for thousand). This would be removed and the subsequent values multiplied by 1000000 and 1000 respectively.
> 9. Contract column has date for players on active contract, and string (free and on loan) for those who are not.
> 10. Hits contains null/missing values which should be resolved.

The dataset was cleaned using a variety of techniques such as python functions, lambda function, split method(), astype() as well as some bit of feature engineering. The #DataChallenge was a good way for me to challenge my data cleaning skill, improve on it as well as meet and connect with other amazing data analysts.
