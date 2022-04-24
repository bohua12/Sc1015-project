# Sc1015-project

## About
This is our Mini-Project for SC1015 which focuses on finding out the main drivers of HDB resale prices, and how much they affect the resale prices. We not only looked into the common drivers such as lease commence date or flat type, we take other variables like 'distance from mrt' into account.

## Contributors
 - @ bohua12: Data Preparation, Random Forest and XGBoost
 - @ Shreyas-hacker : Data Preparation and KNeighborsRegression
 - @ kimtorl: Expolatory Data Analysis

## Motivation 
As university students, housing will soon be our concern as we graduate and step into workforce. HDB BTO flats is seen as an affordable option, and is good investment when we resell it in the future
Through this project, we hope to make a more wise and informed choice on housing, by investigating more about HDB resale price so that we can maximise our profits when we re-sell the HDB flats after we BTO


## Problem Definiton
 - What are main drivers of HDB resale price
 - What should we look out for to maximise the value when we BTO

## Datasets
- [HDB housing data set](https://data.gov.sg/dataset/resale-flat-prices)
- [MRT station coordinates](https://www.kaggle.com/datasets/yxlee245/singapore-train-station-coordinates)

## Machine Learning Algorithms used
- K-nearest Neighbours Regressor (Regression)
- Random Forest (Classification)
- XGBoost (Classificaiton)

## Conclusion
- Remaining lease has minimum correlation with resale price unexpectedly, so it seems to be less important factor affecting HDB resale prices
- Lease commence date and floor area is important variables as they have high correlation and linearity with HDB resale price
- Storey range, flat level and flat type are important variables that cause variations to HDB sale prices, while town seems to be less important

## What did we learn from this project
- We used an extremely large dataset with over 800k entries, which mean certain data processing took extremely long. Thus, we had to adapt in different ways to increase efficiency.
- We also learnt and applied Random Forest and XG boost, which are Machine Learning Algorithms not taught in the course 
- We were able to apply Data science concepts taught in this course, like visualisation tools and tools to evaluate models
- We learnt how to use APIs, which wasnt taught in the course
- We also learnt about the usage of github and information about HDB flats 

## Special thanks
We would like to give appreciation to our Lab TA, Guo Xiao Bao of NTU SCSE for being patient ever responsive to our quieries even beyond office hours and on weekends

## Note
As the file size of one of the csv file, resale_complete which is required for the jupyter notebook, is beyond the file limit(100mb) accepted by github, it can be download [here](https://drive.google.com/file/d/1x5juTwSOfCsHYiD_a1RrG561uYJYmn5c/view?usp=sharing)

## References
- https://data.gov.sg/dataset/resale-flat-prices
- https://www.singstat.gov.sg/whats-new/latest-news/cpi-highlights
- https://developers.onemap.sg/commonapi/search?returnGeom=Y&getAddrDetails=Y&pageNum=1&searchVal=
- https://www.kaggle.com/datasets/yxlee245/singapore-train-station-coordinates
- https://www.kaggle.com/code/teyang/drivers-of-hdb-resale-price-and-prediction/notebook
