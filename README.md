# Sc1015-project
--------

## About
This is our Mini-Project for SC1015 which focuses on finding out the main drivers of HDB resale prices, and how much they affect the resale prices. We not only looked into the common drivers such as lease commence date or flat type, we take other variables like 'distance from mrt' into account.

## Contributors
--------
@ bohua12
@ Shreyas-hacker
@ kimtorl


## Problem Definiton
--------
 - What are main drivers of HDB resale price
 - What should we look out for to maximise the value

## Conclusion
- Remaining lease has minimum correlation with resale price unexpectedly, so it seems to be less important factor affecting HDB resale prices
- Lease commence date and floor area is important variables as they have high correlation and linearity with HDB resale price
- Storey range, flat level and flat type are important variables that cause variations to HDB sale prices, while town seems to be less important

## What did we learn from this project
- We used an extremely large dataset with over 800k entries, which mean certain data processing took extremely long. Thus, we had to adapt in different ways to increase efficiency.
- We also learnt and applied Random Forest and XG boost, which are Machine Learning Algorithms not taught in the course 
- We were able to apply Data science concepts taught in this course, like visualisation tools and tools to evaluate models
- We learnt how to use APIs, which wasnt taught in the course
- We also learnt about github and hdb 

## References
- https://data.gov.sg/dataset/resale-flat-prices
- https://www.singstat.gov.sg/whats-new/latest-news/cpi-highlights
- https://developers.onemap.sg/commonapi/search?returnGeom=Y&getAddrDetails=Y&pageNum=1&searchVal=
- https://www.kaggle.com/datasets/yxlee245/singapore-train-station-coordinates
- https://www.kaggle.com/code/teyang/drivers-of-hdb-resale-price-and-prediction/notebook
