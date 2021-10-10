# BigData

We were asked to work on the Amazon Vine Program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, we had access to the Amazon Vine program for the outdoor products. We were asked to compare the results between the members who are asked to summit a review, and the non-members who can summit a review but it is optionnal. The main focus of our analysis is to highlight if the Vine program introduce a positive bias in the rating provided by the Vine members.

## 1. Main results

Fistable, we have filtered our dataset in order to keep only the reviews with a total number of votes equal or greater than 20. We have made the hypothesis that those reviews would be more likely to be helpful for the manufacturers. 

On a total of 39,976 reviews, 70% of the reviews ( (28,070 reviews) were prodived by the Vine members and 30% by non-Vine members. Among those reviews, 52.7% (21,061 reviews) were 5 star rating. The Vine members have provided 14,922 5 star rating, representing a total of 70.8% of the total of the 5 star rating reviews. 

Among the total of the Vine members reviews, 53.16% have a 5 star rating. Among the non-Vine members, the percentage of 5 star rating is 51.56%.

## 2. Summary

With the above results, we could conclude that the Vine program is introducing a positive bias in the reviews provided by the members. However, the bias seems limited. In order to be able to confirm this positive bias, we have provided a last analysis. We have calculated the percentage of reviews which have a rating equal or inferior to 2. Our focus is to confirm if the Vine program could exagerate the positive reviews provided by the members. Among the reviews provided by the Vine members, 18.42% are negative reviews with a rating equal or inferior to 2. Among the non-Vine members, this percentage is 21.58%. These results support our first conclusion: the Vine program tends to introduce a positive bias in the reviews provided by their members.
