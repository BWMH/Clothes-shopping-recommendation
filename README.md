![My Image](images/recommendation.png)
# Clothes shopping recommendation
This project aims to improve customer shopping enthusiasm and online shopping experiences. It details and explains the model used for recommending shop items that users have a high possibility to purchase and the comparison between several approaches to predicting similarities and thus recommendation.
The experimental results show that by measuring user similarity, specifically between purchase and rating history, one is able to more precisely predict user ratings for items that have not yet been purchased by the user and coincidentally curate a list of (new) items that the user is highly likely to purchase and rate high.
Results from this study are not limited to the fashion industry alone. The models can be used in many other industries where user-item ratings are available and rating predictions could influence item recommendation to the users.

The dataset used contains the measurements of clothing fit from RentTheRunway. The data is cited from the report called Decomposing fit semantics for product size recommendation in metric spaces by Rishabh Misra, Mengting Wan, Julian McAuley RecSys, 2018.

Results of the study show that among several models, the Bag of Words is the best performing model for the objective of using text-mining for rating prediction, with reaches a MSE of 2.073.
