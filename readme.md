# Exploration of Amazon consumer products reviews
## by Kyle McMillan


## Dataset

The dataset is approximately 7 million reviews from Amazon's US marketplace. The 
reviews are from 1996 to 2006 and included 38 categories. The reviews contain 
the star rating, and helpfulness of the review to other by the way of votes against 
the review. The dataset also includes the full title and body of the review that 
was made, as well as other aspects of the review. Details and feature documentation 
about the dataset can be found in Amazon review dataset index.txt.


## Summary of Findings

An interesting point that I discovered early on was that the majority, more than 4 
million, of the stars given to a review were a perfect 5 star rating. I also found 
that a lot of customers only made 1 review. Since there was a often a large difference, 
100,000+ points, using a linear scale made many of the graphs unreadable and as such
I had to put the y-axis on the graphs to log scale. In the exploration I found the 
strongest relationship was between the total number of votes and the number of helpful 
votes, but that can be expected as the more total votes there are, the greater the 
number of helpful votes there will be. As such these 2 features had a linear relationship. 
An interesting point I found was that there was a small relationship between 1 and 2 
star ratings and the number of total and helpful votes. There is also interesting 
relationships with vine reviewers. In both cases of, on average, vine reviews having 
more helpful votes as well as having a longer word count.

Outside of the main points of interest, I found that there are longer average word 
count for products in 2 star ratings. While 5 star ratings have the most overall 
reviews, it is also the rating with the lowest average word count for all ratings.
I also found that non-verified purchases are more likely to make longer reviews and 
at the same time, receive more helpful votes to a their review.


## Key Insights for Presentation

For the presentation I focused mainly on the helpful votes against the review body 
word count. I started by looking at the variables of the helpful votes and 
review word counts separately. The helpful votes graph is displayed on a transformed
histogram and the word count is displayed on a violin plot.
Then I plotted both variables against each other on a scatter plot.

Next I introduced the categorical variable of the star rating. Using the same scatter 
plot information above, I split the points by star rating. I made sure to make sure 
that the colours for each point was different, but as there was so many points to plot 
it is difficult to differentiate so I also added in lines of best fit to be able to see 
the trends better.
Finally I compared the average word counts and average helpful votes for each review 
against each star rating. This were placed on the same graph to see a trend between the 
2 numeric variables against star ratings.