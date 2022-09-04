# We Rate Dogs Data 
The dataset that I wrangled (and analyzed and visualized) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
### Assessing Data
I assessed the data for two things: (1) quality and (2) tidiness issue. The quality issues I found in the dataset were:

Missing tweets
Dogs without names
Wrong datatypes, for instance "timesstamp"
duplicated rows in sources column
Redundant retweet rows
Numerators with decimals
Source column in Html
missing images
The tidiness issues I found in the dataset were:

Reduntant columns > doggo, floofer, pupper and puppo columns in twitter_archive_df table should be merged into one column named "dog_stage"
"retweet count" and "favorite count" columns are not in the twitter_archive_df
## Conclusion 
The most liked dog is pupper, followed by doggo, then puppo while the least liked dog is doggo, floofer and doggo, puppo.
Pupper dog is the most popular dog stage since it has the highest number of tweets with () count, followed by doggo with () retweets, puppo with () retweet counts whereas the least popular dog is doggo, floofer.
