# Data Analysis Of WeRateDog Tweets

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Data for this analysis were gathered from three different sources:
- Twitter API
- https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- twitter-archive-enhanced.csv

After successfully gathering the data, extensive wrangling was carried out to have clean data for our analysis.


## Questions answered during analyses
The data analyses would answer the following questions:

* What dogs have the top five retweet count
* what dogs have the least three favorite counts
* What is the total retweet count for each predicted dog breed
* Which predicted dog breed has the highest total retweet count (top 5) for the period under review.
* which dog breed has the highest rating


## Summary of findings

* Dog breeds like labrador_retriever, eskimo_dog, chihuahua, lakeland_terrier, english_springer are among dogs with the highest retweet counts
* labrador_retriever, irish_setter, blenheim_spaniel are among dogs with the least favorite counts
* The maximum dog rating of 42 indicates that there are still outliers or errors in the dataset
* There is a direct relationship between retweet count and favorite count