# Using-mapreduce-on-amazon-reviews
This code loads a json file of amazon games and toys reviews into MongoDB and uses mapreduce function to calculate weighted average scores
The format of "reviews_toys_and_games.json" is as follows:
• reviewerID - ID of the reviewer, e.g. A36NM32UFFE5BO 
• asin - ID of the product, e.g. 048645195X 
• reviewerName - name of the reviewer 
• helpful - helpfulness rating of the review, e.g. 2/3 
• reviewText - text of the review 
• overall - rating of the product 
• summary - summary of the review 
• unixReviewTime - time of the review
