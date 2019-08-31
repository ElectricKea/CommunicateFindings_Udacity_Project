# Exploration of Amazon consumer products reviews
## by Kyle McMillan


## Dataset

The dataset is approximatly 7 million reviews from Amazon's US marketplace. The reviews are from 1996 to 2006 and included 38
categories. The reviews contain the star rating, and helpfulness of the review to other by the way of votes against the review. 
The dataset also includes the full title and body of the review that was made, as well as other aspects of the review.
Details and feature documentation about the dataset can be found in Amazon review dataset index.txt.


## Summary of Findings

An interesting point that I discovered early on was that the majority, more than 4 million, of the stars given to a review 
were a perfect 5 star rating. I also found that a lot of customers only made 1 review.
Since there was a often a large difference, 100,000+ points, using a linear scale made many of the graphs unreadable and as such
I had to put the y-axis on the graphs to log scale.
In the exploration I found the strongest relationship was between the total number of votes and the number of helpful votes, 
but that can be expected as the more total votes there are, the greater the number of helpful votes there will be. As such 
these 2 features had a linear relationship. 
An interesting point I found was that there was a small relationship between 1 and 2 star ratings and the number of total and 
helpful votes. There is also interesting relationships with vine reviewers. In both cases of, on average, vine reviews having 
more helpful votes as well as having a longer word count.

Outside of the main points of interest, I found that there are longer average word count for products in 2 star ratings. While 5 star ratings have the most overall reviews, it is also the rating with the lowest average word count for all ratings.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
